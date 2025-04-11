---
title: Lucky Draw

---

<script src="https://cdn.sheetjs.com/xlsx-latest/package/dist/xlsx.full.min.js"></script>
<style>
    /* Winner List Container */
    #winnerList {
        margin-top: 30px;
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 15px;
    }

    /* Winner Item */
    .winner-item {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 90%;
        max-width: 400px;
        padding: 12px 16px;
        border-radius: 12px;
        font-size: 18px;
        font-weight: 500;
        transition: background-color 0.3s ease, border 0.3s ease, color 0.3s ease;
        background-color: rgb(var(--color-primary-50));
        border: 2px solid rgb(var(--color-primary-200));
        color: rgb(var(--color-primary-800));
        box-shadow: 0 4px 8px rgba(var(--color-primary-700), 0.08);
    }

    /* Dark mode styles for winner-item */
    .dark .winner-item {
        background-color: rgb(var(--color-primary-950));
        border: 2px solid rgb(var(--color-primary-800));
        color: rgb(var(--color-primary-100));
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
    }

    /* Remove Button */
    button.remove-btn {
        background-color: rgb(var(--color-primary-500));
        border: none;
        color: white;
        padding: 6px 12px;
        border-radius: 8px;
        font-size: 14px;
        cursor: pointer;
        transition: background-color 0.2s ease;
    }

    button.remove-btn:hover {
        background-color: rgb(var(--color-primary-700));
    }

    /* Dark mode button style */
    .dark button.remove-btn {
        background-color: rgb(var(--color-primary-600));
    }

    .dark button.remove-btn:hover {
        background-color: rgb(var(--color-primary-400));
    }
</style>

<input type="file" id="upload" accept=".xlsx" />
<br><br>
<button onclick="drawWinner()">Draw Winner</button>
<div id="winnerList"></div>


<script>
    let names = [];
    let winners = [];
    let excludedNames = [];

    document.getElementById('upload').addEventListener('change', (e) => {
        const file = e.target.files[0];
        if (!file) return;

        const reader = new FileReader();
        reader.onload = (evt) => {
            const data = evt.target.result;
            const workbook = XLSX.read(data, { type: 'binary' });
            const firstSheet = workbook.Sheets[workbook.SheetNames[0]];
            const jsonData = XLSX.utils.sheet_to_json(firstSheet);

            console.log("Parsed Data:", jsonData);

            names = jsonData.map(row => row.Name).filter(name => !!name);
            winners = []; // Reset winners on new upload
            updateWinnerList();

            if (names.length === 0) {
                alert("No 'Name' column found or it's empty.");
            }
        };
        reader.readAsBinaryString(file);
    });

    function drawWinner() {
        if (names.length === 0) {
            alert("Please upload a valid Excel file first.");
            return;
        }

        if (winners.length >= 3) {
            alert("You've already drawn 3 winners.");
            return;
        }

        const remainingNames = names.filter(
            name => !winners.includes(name) && !excludedNames.includes(name)
        );

        if (remainingNames.length === 0) {
            alert("No more unique names to draw.");
            return;
        }

        const randomIndex = Math.floor(Math.random() * remainingNames.length);
        const winnerName = remainingNames[randomIndex];
        winners.push(winnerName);
        updateWinnerList();
    }

    function updateWinnerList() {
        const container = document.getElementById('winnerList');
        container.innerHTML = '';

        winners.forEach((name, index) => {
            const div = document.createElement('div');
            div.className = 'winner-item';
            div.innerHTML = `
          ${name}
          <button class="remove-btn" onclick="removeWinner(${index})">Remove</button>
        `;
            container.appendChild(div);
        });
    }

    function removeWinner(index) {
        const removed = winners.splice(index, 1)[0];
        excludedNames.push(removed); // 🔥 Permanently exclude
        updateWinnerList();
    }
</script>
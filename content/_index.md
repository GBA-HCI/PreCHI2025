---
title: 'Home'
date: 2025-03-07
type: landing

design:
  # Default section spacing
  spacing: "4rem"

sections:
  - block: hero
    content:
      image:
        # Add your image background to `assets/media/`.
        filename: bg-gba.jpg
        filters:
          brightness: 0.5
      title: GBA HCI Pre-CHI 2025
      text: April 12th, 2025 in City University of Hong Kong
      primary_action:
        text: Register a Talk/Poster
        url: "https://bespoke-profiterole-9c46e8.netlify.app/"
      secondary_action:
        text: Register as an Audience
        url: https://beamish-marzipan-ec0d47.netlify.app/
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-gba.jpg
          filters:
            brightness: 0.5
  - block: my-card
    id: about
    content:
      text: '
      <div class="max-w-6xl mx-auto px-2 bg-white rounded-xl">
        <div class="grid justify-center gap-x-2" 
             style="grid-template-columns: repeat(auto-fit, minmax(150px, 1fr))">
          <div class="flex flex-col items-center p-2 min-w-[150px]">
            <div class="w-full aspect-square flex items-center justify-center">
              <img src="media/logos/CityUHK.webp" alt="CityU" class="max-h-full w-auto object-contain">
            </div>
          </div>
          <div class="flex flex-col items-center p-2 min-w-[150px]">
            <div class="w-full aspect-square flex items-center justify-center">
              <img src="media/logos/SUSTech.webp" alt="SUSTech" class="max-h-full w-auto object-contain">
            </div>
          </div>
          <div class="flex flex-col items-center p-2 min-w-[150px]">
            <div class="w-full aspect-square flex items-center justify-center">
              <img src="media/logos/PolyU.webp" alt="PolyU" class="max-h-full w-auto object-contain">
            </div>
          </div>
          <div class="flex flex-col items-center p-2 min-w-[150px]">
            <div class="w-full aspect-square flex items-center justify-center">
              <img src="media/logos/STU.webp" alt="STU" class="max-h-full w-auto object-contain">
            </div>
          </div>
          <div class="flex flex-col items-center p-2 min-w-[150px]">
            <div class="w-full aspect-square flex items-center justify-center">
              <img src="media/logos/HKUST(GZ).webp" alt="HKUST(GZ)" class="max-h-full w-auto object-contain">
            </div>
          </div>
          <div class="flex flex-col items-center p-2 min-w-[150px]">
            <div class="w-full aspect-square flex items-center justify-center">
              <img src="media/logos/UM.png" alt="UM" class="max-h-full w-auto object-contain">
            </div>
          </div>
          <div class="flex flex-col items-center p-2 min-w-[150px]">
            <div class="w-full aspect-square flex items-center justify-center">
              <img src="media/logos/HKUST.webp" alt="HKUST" class="max-h-full w-auto object-contain">
            </div>
          </div>
          <div class="flex flex-col items-center p-2 min-w-[150px]">
            <div class="w-full aspect-square flex items-center justify-center">
              <img src="media/logos/SYSU.webp" alt="SYSU" class="max-h-full w-auto object-contain">
            </div>
          </div>
          <div class="flex flex-col items-center p-2 min-w-[150px]">
            <div class="w-full aspect-square flex items-center justify-center">
              <img src="media/logos/SZU.webp" alt="SZU" class="max-h-full w-auto object-contain">
            </div>
          </div>
          <div class="flex flex-col items-center p-2 min-w-[150px]">
            <div class="w-full aspect-square flex items-center justify-center">
              <img src="media/logos/JNU.webp" alt="JNU" class="max-h-full w-auto object-contain">
            </div>
          </div>
        </div>
      </div>


      GBA Pre-CHI 2025 aims to provide a dedicated platform for HCI researchers from the Greater Bay Area (GBA) of China to share their latest work. This includes research to be published at ACM CHI 2025 or other premiere HCI venues, as well as ongoing and exploratory work showcased through poster sessions. There are still slots available for presentations and posters. We welcome more presenters from the GBA region to join us!


      This one-day event will be held exclusively on-site, offering participants an excellent opportunity for face-to-face academic exchanges and collaboration within the HCI community.


      GBA Pre-CHI 2025 旨在为中国大湾区（Greater Bay Area, GBA）的人机交互（Human-Computer Interaction, HCI）研究者提供一个分享和交流其最新研究成果的平台。无论是即将在 ACM CHI 2025 上发表的论文，还是近期在其他顶级 HCI 会议上发表的研究，均可在本次研讨会上展示。活动同时设有海报展示，为尚未提交或正在进行的研究提供交流机会。目前仍有部分报告和展报名额，欢迎大湾区的学生和老师们继续踊跃报名。
      

      本次研讨会为期一天，仅限线下进行。我们期待与来自大湾区及其他地区的学者共同探讨 HCI 领域的前沿问题，并通过面对面的交流促进学术合作与创新。
      '
    design:
      text:
        # Card background color (CSS class)
        css_class: "text-black dark:text-gray-100"
        css_style: "text-align: left;"
  - block: program
    id: program
    content:
      title: "Tentative Program"
      text: 
      timeslots:
        - time: "09:00 - 09:20"
          title: Welcome Reception
          sessions: 
          - name: '[leave your comments]({{< relref "/program/welcome" >}})'
            location: "Yeung LT-17"
        - time: 09:20 - 09:50
          title: Opening Keynote
          sessions: 
          - name: |
                  Prof. Xiaohua Sun
                  
                  Southern University of Science and Technology
            location: CMC M505
        - time: 10:00 - 12:00
          hr: 1
          title: Session A
          sessions: 
          - name: A-1 Track
            location: Yeung LT-17
            topic: 'GenAI in everyday life'
          - name: A-2 Track
            location: Yeung LT-18
            topic: Technology-Enhanced Learning 
        - time: 12:00 - 13:00
          hr: 1
          sessions: 
          - name: "Lunch Break & Poster & Group Photo Taking"
            location: "The Hall Way between LT-17 and LT-18"
        - time: 13:00 - 15:15
          hr: 1
          title: Session B
          sessions: 
          - name: B-1 Track
            location: Yeung LT-17
            topic: Interactive Systems and Data Visualization
          - name: B-2 Track
            location: Yeung LT-18
            topic: Collaborative and Creative Research Methodology
        - time: 15:15 - 16:00
          hr: 1
          sessions: 
          - name: "Tea Break and Poster Session"
            location: "The Hall Way between LT-17 and LT-18"
        - time: 16:00 - 18:00
          hr: 1
          title: Session C
          sessions: 
          - name: C-1 Track
            location: LT-17
            topic: Human-Centered Healthcare
          - name: C-2 Track
            location: LT-18
            topic: Interaction in VR/AR  
        - time: 18:00 - 18:30
          hr: 1
          title: "Closing Keynote"
          sessions: 
          - name: |
                   Prof. Haining Liang

                   The Hong Kong University of Science and Technology (Guangzhou)
            location: "LT-17"
        - time: 18:30 - 18:50
          title: "Award Ceremony"
          sessions:
          - name: 
            location: "LT-17" 
        # - time: 18:45 - 20:30
        #   title: "Conference Dinner"
        #   sessions: 
        #   - name: 
        #     location: "City Chinese Restaurant, 8/F, Bank of China (Hong Kong) Complex"
    design:
      css_class: "bg-gray-100 dark:bg-transparent"
  - block: my-card
    id: venue
    content:
      title: Venue
      text: |
        The forum will be held at City University of Hong Kong (CityU), located in Kowloon Tong, Kowloon, Hong Kong.
        | Getting to CityU | Campus Maps |
        | --- | --- |
        | Guides on the official website: [[link]](https://www.cityu.edu.hk/about/campus/getting-to-cityu) | Download PDF: [[pdf]](https://www.cityu.edu.hk/cdo/download/CampusDirectory.pdf) |
        | Video guides: [[link]](https://gbahci.com/prechi/cityu/) | Search for buildings: [[link]](https://www.cityu.edu.hk/about/campus/map) |
    design:
      text:
        # Card background color (CSS class)
        css_class: "text-black dark:text-gray-100"
        css_style: "text-align: left;"
  - block: gallery
    id: gallery
    content:
      title: 
      slider: |

        {{< carousel items="1" height="680" unit="px" duration="7000" >}}
      text: |

        The 
        <a href="#gallery" onclick="document.querySelector('.carousel').querySelector('ol li:first-child a').click();">
          advertising poster
        </a> 
        <a href="#gallery" onclick="document.querySelector('.carousel').querySelector('ol li:first-child a').click(); document.querySelector('.carousel').querySelector('ul li:first-child img').requestFullscreen();">
          [full]
        </a> for Pre-CHI 2025 and 
        <a href="#gallery" onclick="document.querySelector('.carousel').querySelector('ol li:first-child').nextElementSibling.querySelector('a').click();document.querySelector('.carousel').querySelector('ul').classList.remove('interacted');">
          photos
        </a> taken at [Pre-CHI 2024](https://gbahci.com/prechi/).

        Stay tuned, and more details will be announced later.
      
    design:
      css_class: "bg-gray-100 dark:bg-transparent"
  - block: people
    id: people
    content:
      title: "Organizing Committees"
      text: ""
      groups:
        - title: "General Chair"
          members:
            - name: "Prof. Yuhan Luo"
              role: "City University of Hong Kong"
              image: people/YuhanLuo.jpg
            - name: "Prof. Can Liu"
              role: "City University of Hong Kong"
              image: people/CanLiu.jpeg
        - title: "Program Chair"
          members:
            - name: "Prof. Xiaoyu Zhang"
              role: "City University of Hong Kong"
              image: people/XiaoyuZhang.jpg
        - title: "Panel Chair"
          members:
            - name: "Prof. Ye Wang"
              role: "University of Macau"
              image: people/YeWang.jpg
        - title: "Poster Chair"
          members:
            - name: "Rui Yao"
              role: "City University of Hong Kong"
              image: people/RuiYao.jpeg
        - title: "Technical Chair"
          members:
            - name: "Hanfang Lyu"
              role: "The Hong Kong University of Science and Technology"
              image: people/HanfangLyu.jpg
        - title: "Student Volunteer Chair"
          members:
            - name: "Zihao Zhu"
              role: "City University of Hong Kong"
              image: people/ZihaoZhu.png
            - name: "Luoying Lin"
              role: "City University of Hong Kong"
              image: people/LuoyingLin.png
  - block: my-card
    id: sponsor
    content:
      title: "Sponsors"
      text: |
        City University of Hong Kong, Department of Computer Science

        K.C. Wong Education Foundation
    design:
      css_class: "bg-gray-100 dark:bg-transparent"
  # - block: stats
#     content:
#       items:
#         - statistic: "1M+"
#           description: |
#             Websites built  
#             with Hugo Blox
#         - statistic: "10k+"
#           description: |
#             GitHub stars  
#             since 2016
#         - statistic: "3k+"
#           description: |
#             Discord community  
#             for support
#     design:
#       # Section background color (CSS class)
#       css_class: "bg-gray-100 dark:bg-transparent"
#       # Reduce spacing
#       spacing:
#         padding: ["1rem", 0, "1rem", 0]
#   - block: features
#     id: features
#     content:
#       title: Features
#       text: Build your site with blocks 🧱
#       items:
#         - name: Optimized SEO
#           icon: magnifying-glass
#           description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
#         - name: Fast
#           icon: bolt
#           description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
#         - name: Easy
#           icon: sparkles
#           description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
#         - name: No-Code
#           icon: code-bracket
#           description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
#         - name: Highly Rated
#           icon: star
#           description: Rated 5-stars by the community.
#         - name: Swappable Blocks
#           icon: rectangle-group
#           description: Build your pages with blocks - no coding required!
#   - block: cta-image-paragraph
#     id: solutions
#     content:
#       items:
#         - title: Build your future-proof website
#           text: As easy as 1, 2, 3!
#           feature_icon: check
#           features:
#             - "Future-proof - edit your content in text files"
#             - "Website is generated by a single app, Hugo"
#             - "No JavaScript knowledge required"
#           # Upload image to `assets/media/` and reference the filename here
#           image: build-website.png
#           button:
#             text: Get Started
#             url: https://hugoblox.com/templates/
#         - title: Large Community
#           text: Join our large community on Discord - ask questions and get live responses
#           feature_icon: bolt
#           features:
#             - "Dedicated support channel"
#             - "3,000+ users on Discord"
#             - "Share your site and get feedback"
#           # Upload image to `assets/media/` and reference the filename here
#           image: coffee.jpg
#           button:
#             text: Join Discord
#             url: https://discord.gg/z8wNYzb
#     design:
#       # Section background color (CSS class)
#       css_class: "bg-gray-100 dark:bg-transparent"
#   - block: testimonials
#     content:
#       title: ""
#       text: ""
#       items:
#         - name: "Hugo Smith"
#           role: "Marketing Executive at X"
#           # Upload image to `assets/media/` and reference the filename here
#           image: "testimonial-1.jpg"
#           text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
#     design:
#       spacing:
#         # Reduce bottom spacing so the testimonial appears vertically centered between sections
#         padding: ["6rem", 0, 0, 0]
#   - block: cta-card
#     content:
#       title: Build your future-proof website
#       text: As easy as 1, 2, 3!
#       button:
#         text: Get Started
#         url: https://hugoblox.com/templates/
#     design:
#       card:
#         # Card background color (CSS class)
#         css_class: "bg-primary-700"
#         css_style: ""
---

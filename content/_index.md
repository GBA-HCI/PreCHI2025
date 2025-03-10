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


      GBA Pre-CHI 2025 aims to provide a dedicated platform for Human-Computer Interaction (HCI) researchers from the Greater Bay Area (GBA) of China to share their work that is in progress, to be published or has been published at the premiere HCI venues. As the name of the forum suggests, we envision it as a stage for prospective authors to present at the upcoming ACM CHI Conference while also inviting other researchers with publication records to HCI conferences. This one-day event will be held exclusively on-site, with no virtual participation available. 


      本研讨会旨在为中国大湾区的人机交互（HCI）研究者提供一个分享他们近期研究工作的平台，这些工作包括即将在ACM CHI2025 会议上发表的论文成果以及其他在HCI相关会议发表的工作。正如此次活动的名称所示，我们期望这是为即将在ACM CHI会议上发表论文的作者们提供一个舞台，同时也欢迎在HCI会议上有发表记录的其他研究者参与。我们还会组织海报展示会，为那些正在进行和尚未提交的研究工作提供展示空间。该活动为期一天，只限现场参与。


      <b>General Chairs</b>: Prof. Can Liu and Prof. Yuhan Luo 
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
      text: '[[program details]]({{< relref "/program" >}})'
      timeslots:
        - time: "09:00 - 09:20"
          sessions: 
          - name: "Welcome Reception"
            location: "Yeung LT-17"
        - time: 09:20 - 09:50
          sessions: 
          - name: Opening Keynote
            location: CMC M505
        - time: 10:00 - 12:00
          hr: 1
          sessions: 
          - name: Session A-1
            location: Yeung LT-17
            topic: TBD
          - name: Session A-2
            location: Yeung LT-18
            topic: TBD
        - time: 12:00 - 13:00
          hr: 1
          sessions: 
          - name: "Lunch Break & Poster & Group Photo Taking"
            location: "The Hall Way between LT-17 and LT-18"
        - time: 13:00 - 15:15
          hr: 1
          sessions: 
          - name: Session B-1
            location: Yeung LT-17
            topic: TBD
          - name: Session B-2
            location: Yeung LT-18
            topic: TBD
        - time: 15:15 - 16:00
          hr: 1
          sessions: 
          - name: "Tea Break & Poster"
            location: "The Hall Way between LT-17 and LT-18"
        - time: 16:00 - 18:00
          hr: 1
          sessions: 
          - name: Session C-1
            location: LT-17
            topic: TBD
          - name: Session C-2
            location: LT-18
            topic: TBD  
        - time: 18:00 - 18:30
          hr: 1
          sessions: 
          - name: "Closing Keynote & Award Ceremony"
            location: "LT-17"
        - time: 18:45 - 20:30
          sessions: 
          - name: "Dinner"
            location: "City Chinese Restaurant, 8/F, Bank of China (Hong Kong) Complex"
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

        Photos taken at the last year's Pre-CHI forum on April 2024: [[link]](https://gbahci.com/prechi/).

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
  - block: people
    content:
      title: "Student Volunteers"
      text: "Call for Student Volunteers"
      groups:
    design:
      css_class: "bg-gray-100 dark:bg-transparent"
  - block: my-card
    id: sponsor
    content:
      title: "Sponsors"
      text: |
        City University of Hong Kong, Department of Computer Science

        K.C. Wong Education Foundation
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

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
        text: View our photos
        url: "#gallery"
      secondary_action:
        text: View our program
        url: "#program"
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
              <img src="media/logos/cityu.svg" alt="CityU" class="max-h-full w-auto object-contain">
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


      GBA Pre-CHI 2025 aims to provide a dedicated platform for HCI researchers from the Greater Bay Area (GBA) of China to share their latest work. This includes research to be published at ACM CHI 2025 or other premiere HCI venues, as well as ongoing and exploratory work showcased through poster sessions. Registration for presentations and posters is currently closed. We welcome more audiences from the GBA region to join us!


      This one-day event will be held exclusively on-site, offering participants an excellent opportunity for face-to-face academic exchanges and collaboration within the HCI community.


      GBA Pre-CHI 2025 旨在为中国大湾区（Greater Bay Area, GBA）的人机交互（Human-Computer Interaction, HCI）研究者提供一个分享和交流其最新研究成果的平台。无论是即将在 ACM CHI 2025 上发表的论文，还是近期在其他顶级 HCI 会议上发表的研究，均可在本次研讨会上展示。活动同时设有海报展示，为尚未提交或正在进行的研究提供交流机会。目前演讲和海报报名已截止，欢迎大湾区的学生和老师们踊跃报名参会。
      

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
      title: "Program"
      text: ''
      timeslots:
        - time: "09:00 - 09:20"
          title: Welcome Reception
          sessions: 
            - topic: 'leave your comments'
              location: "[Yeung LT-17](https://cityu.zoom.us/j/86042888488?pwd=VaJZhAsi3YwtOVaHGFqkimYe0yYLIs.1)"
              link: "program/welcome/#comentario"
        - time: 09:20 - 09:50
          title: Opening Keynote
          sessions: 
            - name: 'Prof. Xiaohua Sun'
              location: '[Yeung LT-17](https://cityu.zoom.us/j/86042888488?pwd=VaJZhAsi3YwtOVaHGFqkimYe0yYLIs.1)'
              topic: 'HCI for the Symbiosis with Agentic Machines'
              link: "program/welcome/#opening-keynote---hci-for-the-symbiosis-with-agentic-machines"
        - time: 10:10 - 12:00
          hr: 1
          title: Session 1
          sessions:             
            - name: Session A1
              location: "[Yeung LT-17](https://cityu.zoom.us/j/86042888488?pwd=VaJZhAsi3YwtOVaHGFqkimYe0yYLIs.1)"
              topic: GenAI-Enhanced Communication
              host: Zeyu Huang
              link: program/session_a1
              talks:
              - id: '#rambler-in-the-wild-a-diary-study-of-llm-assisted-writing-with-speech'
                title: '[CHI25] Rambler in the Wild: A Diary Study of LLM-Assisted Writing With
                  Speech'
                speaker: Xuyu Yang
              - id: '#scaffolded-turns-and-logical-conversations-designing-humanized-llm-powered-conversational-agents-for-hospital-admission-interviews'
                title: '[CHI25] Scaffolded Turns and Logical Conversations: Designing Humanized
                  LLM-Powered Conversational Agents for Hospital Admission Interviews'
                speaker: Dingdong Liu
              - id: '#ronaldos-a-poser-how-the-use-of-generative-ai-shapes-debates-in-online-forums'
                title: '[CHI25] "Ronaldo''s a poser!": How the Use of Generative AI Shapes Debates
                  in Online Forums'
                speaker: Yuhan Zeng
              - id: '#journalaide-empowering-older-adults-in-digital-journal-writing'
                title: '[CHI25] JournalAIde: Empowering Older Adults in Digital Journal Writing'
                speaker: Shixu Zhou
              - id: '#harmonycut-supporting-creative-chinese-paper-cutting-design-with-form-and-connotation-harmony'
                title: '[CHI25] HarmonyCut: Supporting Creative Chinese Paper-cutting Design with
                  Form and Connotation Harmony'
                speaker: Huanchen Wang
              - id: '#acknowledge-a-computational-framework-for-human-compatible-affordance-based-interaction-planning-in-real-world-contexts'
                title: '[CHI25] ACKnowledge: A Computational Framework for Human Compatible Affordance-based
                  Interaction Planning in Real-world Contexts'
                speaker: Ziqi Pan
              - id: '#exploring-the-design-of-llm-based-agent-in-enhancing-self-disclosure-among-the-older-adults'
                title: '[CHI25] Exploring the Design of LLM-based Agent in Enhancing Self-disclosure
                  Among the Older Adults'
                speaker: Yijie Guo
            - name: Session B1
              location: "[Yeung LT-18](https://cityu.zoom.us/j/83405519792?pwd=p7KqBgxM6DmDCKd0B63aYezk9WqDbT.1)"
              topic: Healthcare and Human Wellbeing
              host: Liangwei Wang
              link: program/session_b1
              talks:
              - id: '#empathy-driven-interaction-design-guest-talk'
                title: '[Guest Talk] Empathy-Driven Interaction Design'
                speaker: Wei Liu
              - id: '#a-constructed-response-designing-and-choreographing-robot-arm-movements-in-collaborative-dance-improvisation'
                title: "[CHI25] Can AI Prompt Humans? Multimodal Agents Prompt Players' Game Actions and Show Consequences to Raise Sustainability Awareness"
                speaker: Ray Lc
              - id: '#human-precision-medicine-interaction-public-perceptions-of-polygenic-risk-score-for-genetic-health-prediction'
                title: '[CHI25] Human-Precision Medicine Interaction: Public Perceptions of Polygenic
                  Risk Score for Genetic Health Prediction'
                speaker: Yuhao Sun
              - id: '#designing-and-evaluating-a-narrative-driven-spatial-visualization-for-improving-patient-centered-communication-among-older-adults'
                title: '[CHI25] Designing and Evaluating a Narrative-driven Spatial Visualization
                  for Improving Patient-centered Communication among Older Adults'
                speaker: Jiaan Li
              - id: '#walk-in-their-shoes-to-navigate-your-own-path-learning-about-procrastination-through-a-serious-game'
                title: '[CHI 25] Walk in Their Shoes to Navigate Your Own Path: Learning About
                  Procrastination Through A Serious Game'
                speaker: Runhua Zhang
              - id: '#customizing-emotional-support-how-do-individuals-construct-and-interact-with-llm-powered-chatbots'
                title: '[CHI25] Customizing Emotional Support: How Do Individuals Construct and
                  Interact With LLM-Powered Chatbots'
                speaker: Xi Zheng
              - id: '#becoming-my-own-audience-how-dancers-react-to-avatars-unlike-themselves-in-motion-capture-supported-live-improvisational-performance'
                title: '[CHI25] "Becoming My Own Audience": How Dancers React to Avatars Unlike
                  Themselves in Motion Capture-Supported Live Improvisational Performance'
                speaker: Fan Zhang
        - time: 10:30 - 12:00
          # hr: 1
          # title: Panel 1
          sessions:
            - name: 'Panel 1'
              topic: |
                    From LinkedIn to Workplace: Career Opportunities for HCI Graduates
              location: "[Yeung LT-15](https://cityu.zoom.us/j/87806999124?pwd=QSszak2xTj5I5SkFGdnA77F5cQbGkb.1)"
              link: "program/panel1"
              host: 'Yi Xu'
              talks:
                - title: 'Panel Host:'
                  speaker: 'Prof. Xiaoyu Zhang'
                - title: 'Panelists:'
                  speaker: |
                    - Yun Wang (MSRA)
                    - Wynn Lyu (Hong Kong Productivity Council)
                    - Prof. Zhenhui Peng (Sat-Yat Sen University)
                    - Prof. Yingying She (Xiamen University)
                    - Prof. Wei Liu (SUSTech)
        - time: 12:00 - 13:30
          hr: 1
          title: "Lunch Break"
          sessions: 
            - name: "Lunch & Poster & Group Photo Taking"
              location: "The Hall Way between LT-17 and LT-18"
        - time: 13:30 - 15:00
          hr: 1
          title: Session 2
          sessions: 
            - name: Session A2
              location: "[Yeung LT-17](https://cityu.zoom.us/j/86042888488?pwd=VaJZhAsi3YwtOVaHGFqkimYe0yYLIs.1)"
              topic: Interactive Systems and Data Visualization
              host: Xi Zheng
              link: program/session_a2
              talks:
              - id: '#making-invisible-dynamics-visible-case-studies-in-visualizing-computational-and-behavioral-processes-guest-talk'
                title: '[Guest Talk] Making Invisible Dynamics Visible: Case Studies in Visualizing
                  Computational and Behavioral Processes'
                speaker: Yuxin Ma
              - id: '#vizta-enhancing-comprehension-of-distributional-visualization-with-visual-lexical-fused-conversational-interface'
                title: '[EuroVis] VIzTA: Enhancing Comprehension of Distributional Visualization
                  with Visual-Lexical Fused Conversational Interface'
                speaker: Liangwei Wang
              - id: '#insightbridge-enhancing-empathizing-with-users-through-real-time-information-synthesis-and-visual-communication'
                title: '[CHI25] InsightBridge: Enhancing Empathizing with Users through Real-Time
                  Information Synthesis and Visual Communication'
                speaker: Yue Zhang
              - id: '#interlink-linking-text-with-code-and-outputs-in-computational-notebooks'
                title: '[CHI25] InterLink: Linking Text with Code and Outputs in Computational
                  Notebooks'
                speaker: Yanna Lin
              - id: '#creative-blends-of-visual-concepts'
                title: '[CHI25] Creative Blends of Visual Concepts'
                speaker: Yaozhen Zhang
              - id: '#gencolor-generative-color-concept-association-in-visual-design'
                title: '[CHI25] GenColor: Generative Color-Concept Association in Visual Design'
                speaker: Yihan Hou
            - name: Session B2
              location: "[Yeung LT-18](https://cityu.zoom.us/j/83405519792?pwd=p7KqBgxM6DmDCKd0B63aYezk9WqDbT.1)"
              topic: New Media and Research Inspirations
              host: Hanfang Lyu
              link: program/session_b2
              talks:
              - id: '#design-futures-in-hci-design-thinking-for-digital-transformation-guest-talk'
                title: '[Guest Talk] Design Futures in HCI: Design Thinking for Digital Transformation '
                speaker: Zhiyong Fu
              - id: '#participatory-design-in-human-computer-interaction-cases-characteristics-and-lessons'
                title: '[CHI25] Participatory Design in Human-Computer Interaction: Cases, Characteristics,
                  and Lessons'
                speaker: Xiang (nathan) Qi
              - id: '#seqr-a-user-friendly-and-secure-by-design-configurator-for-enterprise-wi-fi'
                title: '[CHI25] SeQR: A User-Friendly and Secure-by-Design Configurator for Enterprise
                  Wi-Fi'
                speaker: Sze Yiu Chau
              - id: '#signaling-human-intentions-to-service-robots-understanding-the-use-of-social-cues-during-in-person-conversations'
                title: '[CHI25] Signaling Human Intentions to Service Robots: Understanding the
                  Use of Social Cues during In-Person Conversations'
                speaker: Hanfang Lyu
              - id: '#exploring-the-evolvement-of-user-engagement-in-online-creative-community-under-the-surge-of-generative-ai-a-case-study-of-deviantart'
                title: '[CSCW] Exploring the Evolvement of User Engagement in Online Creative Community under the Surge of Generative AI: A Case Study of DeviantArt'
                speaker: Kangyu Yuan
              - id: '#designing-highly-accessible-xr-interfaces-rep'
                title: '[REP] Designing Highly Accessible XR Interfaces'
                speaker: Yang Tian
            - name: 'Panel 2'
              topic: |
                    Opportunities and Challenges in Human-Computer Interaction Research in the Greater Bay Area
              location: "[Yeung LT-15](https://cityu.zoom.us/j/87806999124?pwd=QSszak2xTj5I5SkFGdnA77F5cQbGkb.1)"
              link: "program/panel2"
              host: 'Zhuangtong Huang'
              talks:
                - title: 'Panel Host:'
                  speaker: 'Prof. Ye Wang'
                - title: 'Panelists:'
                  speaker: |
                    - Prof. Shengdong Zhao (CityUHK)
                    - Prof. Huaming Qu (HKUST)
                    - Prof. Boyu Gao (Jinan University)
                    - Prof. Pengcheng An (SUSTech) 
                    - Prof. Guihuan Feng (Nanjing University)
        - time: 15:00 - 15:30
          hr: 1
          title: "Tea Break"
          sessions: 
            - name: "Snacks & Poster Session"
              location: "The Hall Way between LT-17 and LT-18"
        - time: 15:30 - 17:00
          hr: 1
          title: Session 3
          sessions: 
            - name: Session A3
              location: "[Yeung LT-17](https://cityu.zoom.us/j/86042888488?pwd=VaJZhAsi3YwtOVaHGFqkimYe0yYLIs.1)"
              topic: Technology-Enhanced Learning and Heritage
              host: Yu'an Chen
              link: program/session_a3
              talks:
              - id: '#culture-inheritance-and-design-innovation-research-practice-at-milab-guest-talk'
                title: '[Guest Talk] Culture Inheritance and Design Innovation: Research Practice
                  at MILAB'
                speaker: Haipeng Mi
              - id: '#coknowledge-supporting-assimilation-of-time-synced-collective-knowledge-in-online-science-videos'
                title: '[CHI25] CoKnowledge: Supporting Assimilation of Time-synced Collective
                  Knowledge in Online Science Videos'
                speaker: Yuanhao Zhang
              - id: '#designing-llm-powered-multimodal-instructions-to-support-rich-hands-on-skills-remote-learning-a-case-study-with-massage-instructors-and-learners'
                title: '[CHI25] Designing LLM-Powered Multimodal Instructions to Support Rich
                  Hands-on Skills Remote Learning: A Case Study with Massage Instructors and Learners'
                speaker: Chutian Jiang
              - id: '#breaking-barriers-or-building-dependency-exploring-team-llm-collaboration-in-ai-infused-classroom-debate'
                title: '[CHI25] Breaking Barriers or Building Dependency? Exploring Team-LLM Collaboration
                  in AI-infused Classroom Debate'
                speaker: Zihan Zhang
              - id: '#litlinker-supporting-the-ideation-of-interdisciplinary-contexts-with-large-language-models-for-teaching-literature-in-elementary-schools'
                title: '[CHI25] LitLinker: Supporting the Ideation of Interdisciplinary Contexts
                  with Large Language Models for Teaching Literature in Elementary Schools'
                speaker: Haoxiang Fan
            - name: Session B3
              location: "[Yeung LT-18](https://cityu.zoom.us/j/83405519792?pwd=p7KqBgxM6DmDCKd0B63aYezk9WqDbT.1)"
              topic: Interaction in VR/AR
              host: Yuan Xu
              link: program/session_b3
              talks:
              - id: '#gazepuffer-hands-free-input-method-leveraging-puff-cheeks-for-vr-guest-talk'
                title: '[Guest Talk] GazePuffer : Hands-Free Input Method Leveraging Puff Cheeks
                  for VR'
                speaker: Minghui Sun
              - id: '#aiget-transforming-everyday-moments-into-hidden-knowledge-discovery-with-ai-assistance-on-smart-glasses'
                title: '[CHI25] AiGet: Transforming Everyday Moments into Hidden Knowledge Discovery
                  with AI Assistance on Smart Glasses'
                speaker: Runze Cai
              - id: '#augmenting-realistic-charts-with-virtual-overlays'
                title: '[CHI25] Augmenting Realistic Charts with Virtual Overlays'
                speaker: Yao Shi
              - id: '#modeling-locomotion-with-body-angular-movements-in-virtual-reality'
                title: '[CHI25] Modeling Locomotion with Body Angular Movements in Virtual Reality'
                speaker: Zijun Mai
              - id: '#vrcaptions-design-captions-for-dhh-users-in-multiplayer-communication-in-vr'
                title: '[CHI25] VRCaptions: Design Captions for DHH Users in Multiplayer Communication
                  in VR'
                speaker: Tianze Xie
              - id: '#reachpad-interacting-with-multiple-virtual-screens-using-a-single-physical-pad-through-haptic-retargeting'
                title: '[CHI25] ReachPad: Interacting with Multiple Virtual Screens using a Single
                  Physical Pad through Haptic Retargeting'
                speaker: Han Shi
        - time: 17:15 - 17:45
          hr: 1
          title: "Closing Keynote"
          sessions: 
            - name: Prof. Haining Liang
              topic: 'XR Gaming: Exploring Future Gameplay Experiences'
              location: "[Yeung LT-17](https://cityu.zoom.us/j/86042888488?pwd=VaJZhAsi3YwtOVaHGFqkimYe0yYLIs.1)"
              link: "program/welcome//#closing-keynote---xr-gaming-exploring-future-gameplay-experiences"
        - time: 17:45 - 18:00
          title: "Award Ceremony"
          sessions:
            - topic: 'leave your comments' 
              location: "[Yeung LT-17](https://cityu.zoom.us/j/86042888488?pwd=VaJZhAsi3YwtOVaHGFqkimYe0yYLIs.1)" 
              link: "program/welcome/#comentario"
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
        | Getting to CityU                                                                                 | Campus Maps                                                                      |
        | ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------- |
        | Guides on the official website: [[link]](https://www.cityu.edu.hk/about/campus/getting-to-cityu) | Download PDF: [[pdf]](https://www.cityu.edu.hk/cdo/download/CampusDirectory.pdf) |
        | Forum guides: [[link]](https://mjrh8ymq6a.feishu.cn/docx/X5qHdmqIMoOgxrxflHTcL4UBngg)            | Search for buildings: [[link]](https://www.cityu.edu.hk/about/campus/map)        |
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

        Photos taken during Pre-CHI 2025 <a href="#gallery" onclick="document.querySelector('.carousel').querySelector('ol li:first-child').querySelector('a').click();document.querySelector('.carousel').querySelector('ul').classList.remove('interacted');">[Group Photo]</a>, the advertising poster <a href="#gallery" onclick="document.querySelector('.carousel').querySelector('ol li:last-child a').click(); document.querySelector('.carousel').querySelector('ul li:last-child img').requestFullscreen();">
          <i class="fa fa-expand" aria-hidden="true"></i> 
        </a>, and the program <a href="uploads/PreCHI Program.pdf" target="_blank">pdf</a> below.
        <hr />
        <embed src="uploads/PreCHI Program.pdf" width="100%" height="680" type="application/pdf">
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

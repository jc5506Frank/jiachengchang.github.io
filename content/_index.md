---
# Leave the homepage title empty to use the site title
title: ''
summary: 'Academic webpage for Jiacheng Chang'
date: 2026-05-03
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: /uploads/resume.pdf
      headings:
        about: 'About Me'
        education: 'Education'
        interests: ''
    design:
      background:
        color: '#f8fafc'

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    id: papers
    content:
      title: Working Papers
      subtitle: ''
      text: |-
        ### Pricing and Addiction Control for Digital Services (2024)

        *Jiacheng Chang, Xiao Lei, and Feng Tian*

        - Major revision at *Manufacturing & Service Operations Management*.
        - Accepted to The 21st Conference on Web and Internet Economics, 2025.
        - Second Place, INFORMS Behavioral Operations Management Best Working Paper Competition, 2025.
        - Finalist, POMS-HK Best Student Paper Award, 2025.
        - SSRN: [https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4962550](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4962550).
        - Media coverage: [Financial Times Chinese](https://wap.ftchinese.com/interactive/200047?exclusive=).

        ### Adaptive Design for In-App Advertising Games: A Data-Driven Methodology Validated with Field Experiments (2025)

        *Jiacheng Chang, Xiao Lei, Zhixi Wan, and Lei Huang*

        - Accepted to The 25th International Conference on Autonomous Agents and Multiagent Systems, 2025.
        - Under review at *Management Science*.
        - SSRN: [https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6137709](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6137709).
    design:
      columns: '1'
      background:
        color: '#ffffff'
  - block: markdown
    id: teaching
    content:
      title: Teaching
      subtitle: ''
      text: |-
        ### The University of Hong Kong

        - Teaching Assistant, MSBA Deep Learning, 2022-2026.
        - Teaching Assistant, MSBA Capstone Project, 2023.

        ### Columbia University

        - Teaching Assistant, BA Capstone Project, 2021.
    design:
      columns: '1'
      background:
        color: '#f8fafc'
  - block: markdown
    id: presentations
    content:
      title: Conference Presentations
      subtitle: ''
      text: |-
        ### Upcoming

        - 2026 INFORMS Annual Meeting, San Francisco, US.
        - 2026 INFORMS Revenue Management and Pricing Conference, Michigan, US.
        - 2026 POMS International Conference in China, Xi'an, China.

        ### 2025

        - The 21st Conference on Web and Internet Economics, New York, US.
        - 2025 POMS International Conference in China, Hainan, China.
        - 2025 INFORMS MSOM Main Conference, London, UK.
        - The 15th POMS-HK International Conference, Hong Kong.

        ### 2024

        - 2024 INFORMS Annual Meeting, Seattle, US.
    design:
      columns: '1'
      background:
        color: '#ffffff'
---

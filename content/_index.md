---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "3rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    id: papers
    content:
      title: 📚 Featured Publication and Conference
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: markdown
    content:
      title: 📚 All Publications
      text: |
        - **Kui An**, Zi-lei Liu, Ting Zhang. et al. Efficient characterizations of multiphoton states with an ultra-thin optical device. **_Nature_ _Communications_** 15, 3944 (2024).
        - Xiao-Xu Fang, **Kui An**, Bai-Tao Zhang, Barry C. Sanders, and He Lu. Maximal coin-position entanglement generation in a quantum walk for the third step and beyond regardless of the initial state. **_Physics_ _Review_ _A_** 107, 012433 (2023).
        - Jing Sun, Guan-qun Yu, **Kui An**. et al. Microwave-induced high-energy sites and targeted energy transition promising for efficient energy deployment. **_Frontiers_ _in_ _Energy_** 16, 931–942 (2022). 
    design:
      columns: '1'
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---

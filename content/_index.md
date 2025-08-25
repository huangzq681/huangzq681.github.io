---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/CV_Huang.pdf
    design:
      css_class: light
      # Avatar customization
      avatar:
        size: large  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
      background:
        color: white
        image:
          # Add your image background to `assets/media/`.
          filename: pattern-randomized.svg
          filters:
            brightness: 1.2
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        <div style="font-size: 0.8em; line-height: 2.0; width: 150%; margin-left: -25%;">
        I am particularly interested in multi-disciplinary climate change fields. My research topics aim to understand the role of water and the associated hydrological processes in regulating global environmental changes in the present and future. While much of my research focuses on the physical mechanisms in climate extremes, e.g., extreme precipitation, heatwaves, floods, and wildfires, I am also interested in how these extremes affect the ecology, human, and socioeconomic systems.  
        Besides the traditional analyzing methods, I am very enthusiastic about using the knowledge of artificial intelligence approaches to comprehend the causes and consequences of these hydrological extremes.
        [More](/research/)
        </div>
      design:
        columns: '1'
    # design:
    #   # columns: '2'
    #   spacing:
    #     padding: ['20px', '0', '20px', '0'] # 调整内边距
    #   css_class: 'full-width' # 添加自定义 CSS 类（如果需要）
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  - block: collection
    id: papers
    content:
      title: Peer-reviewed Journal Articles
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
      count: 0
    design:
      view: citation
  - block: collection
    content:
      title: Co-author Publications
      text: ""
      filters:
        folders:
          - coauthor-publication
        exclude_featured: false
      count: 0
    design:
      view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1

  - block: collection
    id: conferences
    content:
      title: "Conference and Workshop Presentations"
      page_type: talk
      count: 20
      filters:
        exclude_featured: false
      order:
        by: date
        dir: desc
    design:
      view: community/conference
      group_by: date
      group_by_format: "2006"
  
  - block: markdown
    id: news
    content:
      title: 'News'
      subtitle: ''
      text: |-
        <div style="font-size: 0.8em; line-height: 1.5; width: 150%; margin-left: -25%;">

        * 2025-04 — One Earth paper published: Bangladesh storm-tide hazards (with Ravela & Emanuel). （[Link](your-paper-link-here)）

        * 2025-03 — Invited talk at Climate Research Symposium, University of Tokyo.

        * 2025-02 — New collaboration with MIT on extreme weather prediction models.

        * 2025-01 — Featured in Nature Climate Change: "Hydrological extremes in Asia-Pacific region". [Link](your-link-here)

        * 2024-12 — Received Best Paper Award at AGU Fall Meeting 2024.
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']

  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  # - block: cta-card
  #   demo: true # Only display this section in the Hugo Blox Builder demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-
  #       This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

  #       <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

  #       Easily build anything with blocks - no-code required!
        
  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---

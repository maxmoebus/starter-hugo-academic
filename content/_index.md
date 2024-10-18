---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text:
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: ruderboot.jpeg
          filters:
            brightness: 0.3
          size: cover
          position: left
          parallax: true
    # columns: '2'
  # - block: stats
  #   content:
  #     items:
  #       - statistic: "15"
  #         description: |
  #           Publications
  #       - statistic: "1,000+"
  #         description: |
  #           Citations
  #       - statistic: "78"
  #         description: |
  #           h-index
  #   design:
  #     # Section background color (CSS class)
  #     css_class: "bg-gray-100 dark:bg-gray-900"
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  - block: markdown
    content:
      title: About me
      subtitle: ''
      text: |
        I am working as a PhD student with Professor Christian Holz at the [Sensing, Interaction & Perception Lab](https://siplab.org/) at [ETH Zurich](https://inf.ethz.ch/). My focus lies on applying statistics and statistical machine learning to large medical datasets.

        Before joining ETH SIPLAB, I completed the MSc in Statistical Science at the University of Oxford and the BSc in Statistics at University College London (UCL). During my time at the University of Oxford, I worked as a Research Assistant with Dr. Matthias Qian and Professor Mari Sako, where I focused on constructing natural language processing (NLP) models for text classification.

        Besides my studies, I interned in Data Analytics teams at tech companies (Amazon and Auto1 Group), in the Actuarial Science team at an insurance company (Talanx Group) and in Management Consulting (Process Excellence division) at Kienbaum Consultants International (now EY). 

        **Research Interests:**
        - Predictive Medicine & Mobile Health
          - Wrist-worn Wearables
          - Perceived Health
        - Statistical Machine Learning
          - Methods for Event Prediction
          - Methods for Irregular Time Series
          - Causality

    design:
      columns: '2'
      spacing:
         is_fullscreen: true
         padding: ['50px', '0px', '50px', '0px']
  - block: collection
    content:
      title: Recent Publications
      subtitle: ''
      text: |
        You can check out a full list of my publications [<ins>here</ins>](./publication/).
      # Page type to display. E.g. post, talk, publication...
      page_type: publication
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        featured_only: true
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: citation
      # Reduce spacing
      spacing:
         is_fullscreen: true
         padding: ['0px', '20px', '0px', '20px']
---

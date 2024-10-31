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
          filename: optimist.jpeg
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

        My research primarily revolves around biomedical time series for disease modeling and prediction. Initially, I analyzed ratings of perceived health using wearable sensor data in intensive longitudinal studies (see my [<ins>Publications on perceived health</ins>](./tags/perceived-health/)). Since then, I have developed methods to enhance the information extracted from wearables (e.g., [<ins>Nightbeat</ins>](./publication/2024-11-15-bhi-hraccsleep/)) and modeled disease and mortality risk based on wearable sensors at a population scale (see preprints on the UK Biobank). Currently, I am exploring methodologies to link irregular, multimodal biomedical time series to disease outcomes, focusing on interpretability and causality.

        **Research Interests:**
        - Predictive Medicine & Mobile Health
          - Wrist-worn Wearables
          - Perceived Health
        - Statistical Machine Learning
          - Methods for Event Prediction
          - Methods for Multimodal Irregular Time Series
          - Interpretability & Causality
    design:
      spacing:
         is_fullscreen: true
         padding: ['50px', '0px', '50px', '0px']
  - block: collection
    content:
      title: Recent Publications
      subtitle: ''
      text: |
        <div> You can check out a full list of my publications <span class="mybuttons"><a href="/publication/">here</a></span>.</div>

        <div> Most of my past projects have involved <span class="mybuttons"><a href="/tags/interpretable-modeling/">interpretable modeling techniques</a></span> either trying to derive drivers of <span class="mybuttons"><a href="/tags/perceived-health/">perceived health</a></span> rating such as fatigue or sleep quality or in the field of <span class="mybuttons"><a href="/tags/hci/">Human Computer Interaction</a></span>. </div>

      # Page type to display. E.g. post, talk, publication...
      page_type: publication
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

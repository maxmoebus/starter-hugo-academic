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
      button:
        text: Download CV
        url: uploads/Max_Moebus_CV.pdf
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

        My research primarily revolves around biomedical time series for disease (risk) modeling. Initially, I analyzed perceived health using wearable sensor data in intensive longitudinal studies (see my [<ins>Publications on perceived health</ins>](./tags/perceived-health/)). Since then, I have developed new methods to extract information from wearables (e.g., [<ins>Nightbeat</ins>](./publication/2024-11-15-bhi-hraccsleep/)) and modeled disease and mortality risk based on wearable sensors at a population scale on the UK Biobank (currently under review). Currently, I am exploring methodologies to link irregular, multimodal biomedical time series to disease outcomes with a focus on interpretability and causality.

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

        <div>There are a few common themes: <span class="mybuttons"><a href="/tags/interpretable-modeling/">interpretable modeling</a></span>, <span class="mybuttons"><a href="/tags/perceived-health/">perceived health</a></span>, and <span class="mybuttons"><a href="/tags/hci/">Human Computer Interaction</a></span>.
        Most of my past projects involved <span class="mybuttons"><a href="/tags/interpretable-modeling/">interpretable modeling</a></span> techniques to better understand the outcome of interest rather than simply predicting it. A few publications focus on <span class="mybuttons"><a href="/tags/perceived-health/">perceived health</a></span>, such as fatigue or sleep quality, and I've been a sidekick on a few publications in <span class="mybuttons"><a href="/tags/hci/">Human Computer Interaction</a></span>, where I mainly contributed to the (interpretable) statistical analysis.
        
        Below are a some of most recent publications I've been involved in.</div>


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

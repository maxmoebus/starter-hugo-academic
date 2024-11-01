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

        My research primarily revolves around biomedical time series for disease (risk) modeling. Initially, I analyzed perceived health using wearable sensor data in intensive longitudinal studies (see my [<ins>publications on perceived health</ins>](./tags/perceived-health/)). Since then, I have developed new methods to extract information from wearables (e.g., [<ins>Nightbeat</ins>](./publication/2024-11-15-bhi-hraccsleep/)) and modeled disease and mortality risk based on wearable sensors at a population scale on the UK Biobank (currently under review). Currently, I am exploring methodologies to link irregular, multimodal biomedical time series to disease outcomes with a focus on interpretability and causality.

        <a href="/uploads/max_moebus_cv.pdf" target="_blank" class="inline-flex items-center px-4 py-2 text-sm font-medium text-gray-900 bg-white border border-gray-200 rounded-lg hover:bg-gray-100 hover:text-primary-700 focus:z-10 focus:ring-4 focus:outline-none focus:ring-gray-200 focus:text-primary-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700 dark:focus:ring-gray-700"><svg class="w-3.5 h-3.5 me-2.5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
        <path d="M14.707 7.793a1 1 0 0 0-1.414 0L11 10.086V1.5a1 1 0 0 0-2 0v8.586L6.707 7.793a1 1 0 1 0-1.414 1.414l4 4a1 1 0 0 0 1.416 0l4-4a1 1 0 0 0-.002-1.414Z"/>
        <path d="M18 12h-2.55l-2.975 2.975a3.5 3.5 0 0 1-4.95 0L4.55 12H2a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2v-4a2 2 0 0 0-2-2Zm-3 5a1 1 0 1 1 0-2 1 1 0 0 1 0 2Z"/>
        </svg> You can download my CV here.</a>

    design:
      spacing:
         is_fullscreen: true
         padding: ['50px', '0px', '50px', '0px']
  - block: collection
    content:
      title: Recent Publications
      subtitle: ''
      text: |
        <div>Below are a some of the most recent publications I've been involved in. You can check out a full list of my publications <span class="mybuttons"><a href="/publication/">here</a></span>.</div>

        <div>There are a few common themes: <span class="mybuttons"><a href="/tags/interpretable-modeling/">interpretable modeling</a></span>, <span class="mybuttons"><a href="/tags/mobile-health/">mobile health</a></span>, <span class="mybuttons"><a href="/tags/perceived-health/">perceived health</a></span>, and <span class="mybuttons"><a href="/tags/hci/">human computer interaction</a></span>.
        Most of my past projects involved <span class="mybuttons"><a href="/tags/interpretable-modeling/">interpretable modeling</a></span> techniques to better understand the outcome of interest rather than simply predicting it. A few publications focus on <span class="mybuttons"><a href="/tags/perceived-health/">perceived health</a></span>, such as fatigue or sleep quality, and I've been a sidekick on a few publications in <span class="mybuttons"><a href="/tags/hci/">human computer interaction</a></span>, where I mainly contributed to the (interpretable) statistical analysis.</div>


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

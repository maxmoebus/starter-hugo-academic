---
title: "Contimask: Explaining Irregular Time Series via Perturbations in Continuous Time"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Björn Braun
- Christian Holz

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2025-12-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-conference']

# Publication name and optional abbreviated publication name.
publication: In Conference on Neural Information Processing Systems 2025 (NeurIPS: TO APPEAR)
publication_short: at NeurIPS'25 (TO APPEAR)

abstract: >-
  Explaining black-box models for time series data is critical for the wide-scale adoption of deep learning techniques across domains such as healthcare. Recently, explainability methods for deep time series models have seen significant progress by adopting saliency methods that perturb masked segments of time series to uncover their importance towards the prediction of black-box models. Thus far, such methods have been largely restricted to regular time series. Irregular time series, however, sampled at irregular time intervals and potentially with missing values, are the dominant form of time series in various critical domains (e.g., hospital records). In this paper, we conduct the first evaluation of saliency methods for the interpretation of irregular time series models. We first translate techniques for regular time series into the continuous time realm of irregular time series and show under which circumstances such techniques are still applicable. However, existing perturbation techniques neglect the timing and structure of observed data, e.g., informative missingness when data is not missing at random. Thus, we propose Contimask, a simple framework to also apply non-differentiable perturbations, such as simulating that parts of the data had not been observed using NeuroEvolution. Doing so, we are first to successfully detect saliency that is independent of the value of observed data and achieve significant improvements at interpreting irregular time series models on real-world data where 90% of the data is missing.


#summary: We extract HR from wrist-worn accelerometers during sleep by tracing HR curves in the frequncy domain. Our approach further includes motion artifact removal and simple post-processing to bring down the MAE to 0.88 BPM averaged across participants of our novel dataset.
summary: ""

tags:
- Interpretable Modelling

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- 2025-12-02-NeurIPS-Contimask

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "2024-01-01-IScience-MeaningfulDigitalBiomarkersFatigue"` references `content/slides/2024-01-01-IScience-MeaningfulDigitalBiomarkersFatigue/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

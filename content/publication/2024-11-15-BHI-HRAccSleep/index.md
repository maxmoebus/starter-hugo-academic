---
title: "Nightbeat: Heart Rate Estimation From a Wrist-Worn Accelerometer During Sleep"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Lars Hauptmann
- Nicolas Kopp
- Berken Demirel
- Björn Braun
- Christian Holz

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2025-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-02-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In IEEE Journal of Biomedical and Health Informatics (JBHI)
publication_short: In IEEE JBHI (**Oral Presentation at BHI'24**)

abstract: >-
  Today’s fitness bands and smartwatches typically track heart rates (HR) using optical sensors. Large behavioral studies such as the UK Biobank use activity trackers without such optical sensors and thus lack HR data, which could reveal valuable health trends for the wider population. In this paper, we present the first dataset of wrist-worn accelerometer recordings and electrocardiogram references in uncontrolled at-home settings to investigate the recent promise of IMU-only HR estimation via ballistocardiograms. Our recordings are from 42 patients during the night, totaling 310 hours. We also introduce a frequency-based method to extract HR via curve tracing from IMU recordings while rejecting motion artifacts. Using our dataset, we analyze existing baselines and show that our method achieves a mean absolute error of 0.88 bpm—76% better than previous approaches. Our results validate the potential of IMU-only HR estimation as a key indicator of cardiac activity in existing longitudinal studies to discover novel health insights. Our dataset, Nightbeat-DB, and our source code are available on GitHub: https://github.com/eth-siplab/Nightbeat.

#summary: We extract HR from wrist-worn accelerometers during sleep by tracing HR curves in the frequncy domain. Our approach further includes motion artifact removal and simple post-processing to bring down the MAE to 0.88 BPM averaged across participants of our novel dataset.
summary: ""

tags:
- Mobile Health

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
- 2024-11-15-BHI-HRAccSleep

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "2024-01-01-IScience-MeaningfulDigitalBiomarkersFatigue"` references `content/slides/2024-01-01-IScience-MeaningfulDigitalBiomarkersFatigue/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

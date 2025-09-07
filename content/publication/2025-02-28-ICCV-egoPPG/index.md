---
title: "egoPPG: Heart Rate Estimation from Eye-Tracking Cameras in Egocentric Systems to Benefit Downstream Vision Tasks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Björn Braun
- Rayan Armani
- Manuel Meier
- admin
- Christian Holz

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2025-02-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-02-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-conference']

# Publication name and optional abbreviated publication name.
publication: In IEEE/CVF International Conference on Computer Vision (ICCV)
publication_short: In ICCV

abstract: >-
  Egocentric vision systems aim to understand the spatial surroundings and the wearer’s behavior inside it, including motions, activities, and interactions. We argue that egocentric systems must additionally detect physiological states to capture a person’s attention and situational responses, which are critical for context-aware behavior modeling. In this paper, we propose egoPPG, a novel vision task for egocentric systems to recover a person’s cardiac activity to aid downstream vision tasks. We introduce PulseFormer, a method to extract heart rate as a key indicator of physiological state from the eye tracking cameras on unmodified egocentric vision systems. PulseFormer continuously estimates the photoplethysmogram (PPG) from areas around the eyes and fuses motion cues from the headset’s inertial measurement unit to track HR values. We demonstrate egoPPG’s downstream benefit for a key task on EgoExo4D, an existing egocentric dataset for which we find PulseFormer’s estimates of HR to improve proficiency estimation by 14%. To train and validate PulseFormer, we collected a dataset of 13+ hours of eye tracking videos from Project Aria and contact-based PPG signals as well as an electrocardiogram (ECG) for ground-truth HR values. Similar to EgoExo4D, 25 participants performed diverse everyday activities such as office work, cooking, dancing, and exercising, which induced significant natural motion and HR variation (44–164bpm). Our model robustly estimates HR (MAE=7.67bpm) and captures patterns (r=0.85). Our results show how egocentric systems may unify environmental and physiological tracking to better understand users and that egoPPG as a complementary task provides meaningful augmentations for existing datasets and tasks. We release our code, dataset, and HR augmentations for EgoExo4D to inspire research on physiology-aware egocentric tasks.

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
- 2025-02-28-ICCV-egoPPG

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "2024-01-01-IScience-MeaningfulDigitalBiomarkersFatigue"` references `content/slides/2024-01-01-IScience-MeaningfulDigitalBiomarkersFatigue/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

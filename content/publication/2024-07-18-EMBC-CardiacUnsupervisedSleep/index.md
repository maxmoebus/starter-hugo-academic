---
title: "Predicting Sleep Quality via Unsupervised Learning of Cardiac Activity"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Julien Wolfensberger
- Christian Holz

# Author notes (optional)
#author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2024-07-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the 46th Annual International Conference of the IEEE Engineering in Medicine \& Biology Society
publication_short: In *EMBC 2024*

abstract: While highly important for a person’s mood, productivity, and physical performance, perceived sleep quality is challenging to model and, thus, predict with passive means such as physiological and behavioral signals alone. In this paper, we propose a novel method that diverges from traditional feature-based modeling of sleep quality. Instead, our method is unsupervised and derives states of cardiac activity from polysomnography (PSG) recordings of more than 6,800 participants. We then demonstrate that the proportion of time spent in these states strongly correlates with perceived sleep quality using a longitudinal study of 16 participants over one month. Our method classifies participants’ perceived sleep quality with a balanced accuracy of 68%, significantly exceeding prior methods and feature-based approaches that incorporate established metrics of cardiac activity. Interestingly, we find that the states of cardiac activity our method derives oppose traditional sleep stages—even though the states seem easily explainable based on simple metrics of cardiac activity. Thus, we provide evidence that there are still little-understood processes during sleep that need further investigation, potentially even a rethinking of sleep analysis, especially for perceived sleep quality.

# Summary. An optional shortened abstract.
summary: We employ unsupervised learning to detect states of cardiac activity on the large MESA database with more than 6,800 participants. We then show that the proportion of time spent in these states strongly correlates with perceived sleep quality in an intensive longitudinal study. Our mothod stringly outperforms using traditional hand-crafted features of cardiac activity and shows that there are patterns during sleep that we still struggle to understand using traditional modeling techniques.

tags:
- Perceived Health
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
  caption: 'Modeling of perceived sleep quality via the time spent in states of cardiac activity derived via unsupervised learning.'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- 2024-07-18-EMBC-CardiacUnsupervisedSleep
- 2024-07-08-PlosOne-PersonalizedInterpretableSleep
- 2024-08-21-JMIRNT-ANSSleepMS

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "2024-01-01-IScience-MeaningfulDigitalBiomarkersFatigue"` references `content/slides/2024-01-01-IScience-MeaningfulDigitalBiomarkersFatigue/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

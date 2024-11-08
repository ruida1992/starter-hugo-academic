---
title: 'When Moving‐Average Models Meet High‐Frequency Data: Uniform Inference on Volatility'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Rui Da
  - Dacheng Xiu

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2021-11-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
#publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: "*Econometrica*"
#publication_short: In *ICW*

abstract: We conduct inference on volatility with noisy high-frequency data. We assume the observed transaction price follows a continuous-time Itô-semimartingale, contaminated by a discrete-time moving-average noise process associated with the arrival of trades. We estimate volatility, defined as the quadratic variation of the semimartingale, by maximizing the likelihood of a misspecified moving-average model, with its order selected based on an information criterion. Our inference is uniformly valid over a large class of noise processes whose magnitude and dependence structure vary with sample size. We show that the convergence rate of our estimator dominates n1/4 as noise vanishes, and is determined by the selected order of noise dependence when noise is sufficiently small. Our implementation guarantees positive estimates in finite samples.

# Summary. An optional shortened abstract.
#summary: We conduct inference on volatility with noisy high-frequency data. We assume the observed transaction price follows a continuous-time Itô-#semimartingale, contaminated by a discrete-time moving-average noise process associated with the arrival of trades. We estimate volatility, defined as #the quadratic variation of the semimartingale, by maximizing the likelihood of a misspecified moving-average model, with its order selected based on an #information criterion. Our inference is uniformly valid over a large class of noise processes whose magnitude and dependence structure vary with sample #size. We show that the convergence rate of our estimator dominates n1/4 as noise vanishes, and is determined by the selected order of noise dependence #when noise is sufficiently small. Our implementation guarantees positive estimates in finite samples.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Abstract
  url: https://rui-da.netlify.app/publication/rui-econometrica/

url_pdf: 'ECTA15593.pdf'
#url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

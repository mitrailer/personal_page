---
title: "Shortest hyperpaths in a multimodal hypergraph with real-time information on some transit lines"
authors:
- admin
- Angélica Lozano
date: "2019-09-01T00:00:00Z"
doi: "10.1016/j.tra.2019.09.020"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-06T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Transportation Research Part A: Policy and Practice*, In press"
publication_short: "TRA"

abstract: This paper presents an algorithm to find multimodal shortest hyperpaths in a transport system where transit arrival is random (i.e. random-arrival transit system), while real-time information on vehicle arrivals is only available for some lines and modes. When the algorithm is queried, there is a short horizon where real-time information is accurate, and past this the most reliable information for estimating the arrivals is to use a random distribution specific to the lines. This problem occurs frequently in emerging cities where the transit schedules are not maintained. A Combined Real-Time Hypergraph is constructed to model the multimodal transport system where all the public transport modes have random arrivals and real-time information on arrivals is available for some lines of some modes. In order to model the period of time when some lines have real-time information, the composition of the head nodes of hyperarcs changes over time. The algorithm is tested on a real-life transport system where we change the number of lines with available real-time information to assess the performance of the algorithm in different scenarios. We found that incrementing the number of lines with real-time information does not impact the performance.

# Summary. An optional shortened abstract.
summary: An hypergraph model for frequency-based transit with real-time information is presented.

tags:
- hypergraph
- real-time
- multimodal
- transit
- shortest-paths 
featured: false

links:
# - name: "arXiv"
#   url: "https://arxiv.org/abs/1906.06435"
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
  caption: 'Image credit: [**Elsevier**](https://www.journals.elsevier.com/transportation-research-part-c-emerging-technologies)'
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

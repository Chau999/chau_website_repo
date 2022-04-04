---
title: "Learning Inconsistent Preferences with Gaussian processes"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Javier Gonzalez
- Dino Sejdinovic

# Author notes (optional)
author_notes:
- 
- 
- 

date: "2022-03-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Artificial Intelligence and Statistics*
publication_short: In *AISTATS*

abstract: We revisit widely used preferential Gaussian processes (pgp) by Chu et al.(2005) and challenge their modelling assumption that imposes rankability of data items via latent utility function values. We propose a generalisation of pgp which can capture more expressive latent preferential structures in the data and thus be used to model inconsistent preferences, i.e. where transitivity is violated, or to discover clusters of comparable items via spectral decomposition of the learned preference functions. We also consider the properties of associated covariance kernel functions and its reproducing kernel Hilbert Space (RKHS), giving a simple construction that satisfies universality in the space of preference functions. Finally, we provide an extensive set of numerical experiments on simulated and real-world datasets showcasing the competitiveness of our proposed method with state-of-the-art. Our experimental findings support the conjecture that violations of rankability are ubiquitous in real-world preferential data. 

# Summary. An optional shortened abstract.
summary: We challenge the assumption of rankability of duelling data and derive algorithms to model inconsistent preferences. <br /> <br /> *Published in AISTATS 2022*

tags: []

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->
<!-- 
Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->

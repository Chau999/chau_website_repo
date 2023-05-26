---
title: "Gated Domain Units for Multi-source Domain Generalization"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Simon Föll
- Alina Dubatovka
- Eugen Ernst
- admin
- Martin Maritsch
- Patrik Okanovic
- Gudrun Thäter
- Joachim M. Buhmann
- Felix Wortmann
- Krikamol Muandet

# Author notes (optional)
author_notes:
- Joint first
- Joint first
- Joint second
- Joint second
- 
- 
- 
- 
- 
- 

date: "2023-05-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ArXiv
publication_short: In ArXiv

abstract: The phenomenon of distribution shift (DS) occurs when a dataset at test time differs from the dataset at training time, which can significantly impair the performance of a machine learning model in practical settings due to a lack of knowledge about the data’s distribution at test time. To address this problem, we postulate that real-world distributions are composed of latent Invariant Elementary Distributions (I.E.D) across different domains. This assumption implies an invariant structure in the solution space that enables knowledge transfer to unseen domains. To exploit this property for domain generalization, we introduce a modular neural network layer consisting of Gated Domain Units (GDUs) that learn a representation for each latent elementary distribution. During inference, a weighted ensemble of learning machines can be created by comparing new observations with the representations of each elementary distribution. Our flexible framework also accommodates scenarios where explicit domain information is not present. Extensive experiments on image, text, and graph data show consistent performance improvement on out-of-training target domains. These findings support the practicality of the I.E.D assumption and the effectiveness of GDUs for domain generalisation.

# Summary. An optional shortened abstract.
summary: We postulate that real-world distributions are composed of latent Invariant Elementary Distributions across domains and propose Gated Domain Units, a neural network layer to capture a representation for such elemtanry distributions.


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

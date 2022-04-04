---
title: Shapley Values for Model Explanation

event: 
event_url: 

location: Imperial & Oxford StatML Online Seminar Talk 
address:
  # street: 450 Serra Mall
  # city: Stanford
  # region: CA
  # postcode: '94305'
  # country: United States

summary: I presented a variety of model specific SHAP algorithms including my recent contribution RKHS-SHAP.  
abstract: "In this talk we will highlight some recent advancements in using Shapley Values as model interpretability tools. In particular, we will go into model-specific SV methods, such as Linear SHAP for linear models, TreeSHAP for tree models, DeepSHAP for deep models and introduce the latest member to the family — RKHS-SHAP for kernel methods. By analysing Shapley values from a functional perspective, RKHS-SHAP can efficiently compute both interventional and Observational Shapley Values using kernel mean embeddings of distributions, thus avoiding density estimation and sampling as most other methods rely on. We also propose a Shapley regulariser based on RKHS-SHAP that allows learning while controlling the level of specific feature contributions to the model. We demonstrate that the Shapley regulariser enables learning which is robust to covariate shift of a given feature and fair learning which controls the Shapley values of sensitive features. "

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-02-01T10:00:00Z'
date_end: '2022-02-01T11:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2022-02-01T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
<!-- 
{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->

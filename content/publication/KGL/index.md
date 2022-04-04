---
title: "Kernel-based Graph Learning From Smooth Signals: A Functional Viewpoint"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Xingyue Pu
- admin
- Xiaowen Dong
- Dino Sejdinovic

# Author notes (optional)
author_notes:
- 
- 
-
-

date: "2021-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Signal and Information Processing over Networks*
publication_short: In *IEEE*

abstract: The problem of graph learning concerns the construction of an explicit topological structure revealing the relationship between nodes representing data entities, which plays an increasingly important role in the success of many graph-based representations and algorithms in the field of machine learning and graph signal processing. In this paper, we propose a novel graph learning framework that incorporates prior information along node and observation side, and in particular the covariates that help to explain the dependency structures in graph signals. To this end, we consider graph signals as functions in the reproducing kernel Hilbert space associated with a Kronecker product kernel, and integrate functional learning with smoothness-promoting graph learning to learn a graph representing the relationship between nodes. The functional learning increases the robustness of graph learning against missing and incomplete information in the graph signals. In addition, we develop a novel graph-based regularisation method which, when combined with the Kronecker product kernel, enables our model to capture both the dependency explained by the graph and the dependency due to graph signals observed under different but related circumstances, e.g. different points in time. The latter means the graph signals are free from the i.i.d. assumptions required by the classical graph learning models. Experiments on both synthetic and real-world data show that our methods outperform the state-of-the-art models in learning a meaningful graph topology from graph signals, in particular with heavy noise, missing values, and multiple dependency. 

# Summary. An optional shortened abstract.
summary: We proposed a graph learning algorithm to recover topological structure from observed graph signals.

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

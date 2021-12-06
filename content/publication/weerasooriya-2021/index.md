---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Improving Label Quality by Jointly Modeling Items and Annotators
subtitle: ''
summary: ''
authors:
- Tharindu Cyril Weerasooriya
- Alexander G. Ororbia II
- Christopher M. Homan
tags:
- nlp
- pldl
categories:
- PLDL
date: '2021-01-01'
lastmod: 2021-12-06T16:49:47-05:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-12-06T21:49:47.012726Z'
publication_types:
- '2'
abstract: 'We propose a fully Bayesian framework for learning ground truth labels
  from noisy annotators. Our framework ensures scalability by factoring a generative,
  Bayesian soft clustering model over label distributions into the classic David and
  Skene joint annotator-data model. Earlier research along these lines has neither
  fully incorporated label distributions nor explored clustering by annotators only
  or data only. Our framework incorporates all of these properties as: (1) a graphical
  model designed to provide better ground truth estimates of annotator responses as
  input to any black box supervised learning algorithm, and (2) a standalone neural
  model whose internal structure captures many of the properties of the graphical
  model. We conduct supervised learning experiments using both models and compare
  them to the performance of one baseline and a state-of-the-art model.'
publication: '*CoRR*'
links:
- name: URL
  url: https://arxiv.org/abs/2106.10600
---

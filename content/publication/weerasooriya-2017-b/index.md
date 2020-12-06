---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'A framework for automated corpus compilation for KeyXtract: Twitter model'
subtitle: ''
summary: ''
authors:
- Tharindu Weerasooriya
- Nandula Perera
- S. R. Liyanage
tags:
- '"Adaptive"'
- '"Automated Corpus"'
- '"KeyXtract"'
- '"Natural Language Processing"'
- '"Tweets"'
categories: []
date: '2017-01-01'
lastmod: 2020-12-06T11:14:15-05:00
featured: false
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
publishDate: '2020-12-06T16:14:14.969643Z'
publication_types:
- '1'
abstract: The corpus is a limiting factor for a keyword extraction process with a
  word matching stage. This paper proposes a framework to automate the corpus generation
  stage required for the Twitter Model of KeyXtract, an algorithm used for essential
  keyword extraction from tweets. The initial algorithm was designed with two manually
  compiled corpora that limited the adaptability of the system. The automated framework
  proposed in the present research is an extension to the keyword extraction process
  of KeyXtract and would address this limitation of the system. The design was carried
  out using open-class words of the source text and by matching them against the bag
  of words compiled by analyzing the tweets. The automated corpus had a total of 138
  words, out of which 74 words were also found in the handpicked corpus (which had
  a total of 206 words). However, when the corpus was used with the keyword extraction
  system, the average F1 scores of the system showed a decrease of 0.07, proving that
  the automated corpus cannot perform parallel to the human-made corpus in complexity.
  This was because the human-made corpus was compiled using syntactic, semantic and
  pragmatic features while the automated framework focused only on the syntactic features.
  However, there were individual tweets in which the F1 score showed an increase.
  Thus, this was a promising first step in the corpus automation process. The automatic
  corpus generation framework could be made more accurate by including the semantic
  analysis of the lexical items. Thus, the present framework is able to substantially
  address the limitation of the corpus compilation which was present in the Twitter
  Model of KeyXtract.
publication: '*17th International Conference on Advances in ICT for Emerging Regions,
  ICTer 2017 - Proceedings*'
url_pdf: https://ieeexplore.ieee.org/document/8257783
doi: 10.1109/ICTER.2017.8257783
---

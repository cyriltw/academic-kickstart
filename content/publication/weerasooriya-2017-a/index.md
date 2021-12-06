---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A method to extract essential keywords from a tweet using NLP tools
subtitle: ''
summary: ''
authors:
- Tharindu Weerasooriya
- Nandula Perera
- S. R. Liyanage
tags:
- Natural Language Processing
- Turing Test
- Tweet Analysis
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
publishDate: '2021-12-06T21:41:09.732825Z'
publication_types:
- '1'
abstract: A tweet is an authentic use of Natural Language where the user has to deliver
  the message in 140 characters or less. According to previous researchers, this restriction
  increases the possible ambiguity of a tweet making it difficult for traditional
  Natural Language Processing (NLP) tools to analyze it. This research enhances the
  machine learning based Stanford CoreNLP Part-of-Speech (POS) tagger with the Twitter
  model to extract essential keywords from a tweet. The system was enhanced using
  two rule-based parsers and a corpus. The research was conducted using tweets of
  customer service requests sent to a telecommunication company. A domain specific
  corpus was compiled after analyzing the tweets. The POS tagger extracted the keywords
  while the parsers removed any possible noise and extracted any other keywords missed
  by the POS tagger. The evaluation of the system was done using the Turing Test.
  The proposed system was tested and compared against the Stanford CoreNLP. The testing
  was conducted using 6 test cases, each consisting of a human keyword generator and
  a supervisor. In order to ensure the impartiality and intellectual diversity, the
  response generators and supervisors were representatives of 6 different fields.
  As a result of the enhancements, the Turing Test score of the system increased from
  50.00% to 83.33%. The accuracy of the system could be further improved by using
  a complete domain specific corpus. Since the approach used theoretical linguistic
  features of a sentence, the same method could be employed for other NLP tools.
publication: '*16th International Conference on Advances in ICT for Emerging Regions,
  ICTer 2016 - Conference Proceedings*'
url_pdf: https://ieeexplore.ieee.org/document/7829895
doi: 10.1109/ICTER.2016.7829895
links:
- name: URL
  url: https://ieeexplore.ieee.org/document/7829895
---

---
# Documentation: https://wowchemy.com/docs/managing-content/

title: KeyXtract Twitter Model - An Essential Keywords Extraction Model for Twitter
  Designed using NLP Tools
subtitle: ''
summary: ''
authors:
- Tharindu Weerasooriya
- Nandula Perera
- S. R. Liyanage
tags:
- '0'
- '2014'
- '6'
- al
- and pos tagging
- b
- current tools in nlp
- currently
- extraction
- manning et
- open nlp
- stanford corenlp
- version 1
- version 3
- welcome to apache
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
publishDate: '2021-12-06T21:49:48.087338Z'
publication_types:
- '1'
abstract: Since a tweet is limited to 140 characters, it is ambiguous and difficult
  for traditional Natural Language Processing (NLP) tools to analyse. This research
  presents KeyXtract which enhances the machine learning based Stanford CoreNLP Part-of-Speech
  (POS) tagger with the Twitter model to extract essential keywords from a tweet.
  The system was developed using rule-based parsers and two corpora. The data for
  the research was obtained from a Twitter profile of a telecommunication company.
  The system development consisted of two stages. At the initial stage, a domain specific
  corpus was compiled after analysing the tweets. The POS tagger extracted the Noun
  Phrases and Verb Phrases while the parsers removed noise and extracted any other
  keywords missed by the POS tagger. The system was evaluated using the Turing Test.
  After it was tested and compared against Stanford CoreNLP, the second stage of the
  system was developed addressing the shortcomings of the first stage. It was enhanced
  using Named Entity Recognition and Lemmatization. The second stage was also tested
  using the Turing test and its pass rate increased from 50.00% to 83.33%. The performance
  of the final system output was measured using the F1 score. Stanford CoreNLP with
  the Twitter model had an average F1 of 0.69 while the improved system had a F1 of
  0.77. The accuracy of the system could be improved by using a complete domain specific
  corpus. Since the system used linguistic features of a sentence, it could be applied
  to other NLP tools.
publication: '*10th KDU International Research Conference*'
url_pdf: http://arxiv.org/abs/1708.02912
links:
- name: arXiv
  url: https://arxiv.org/abs/1708.02912
- name: URL
  url: http://arxiv.org/abs/1708.02912
---

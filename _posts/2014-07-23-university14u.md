---
abstract: 'The Brown clustering algorithm (Brown et al., 1992) is widely used in natural
  language processing (NLP) to derive lexical representations that are then used
  to improve performance on various NLP problems. The algorithm assumes an underlying
  model that is essentially an HMM, with the restriction that each word in the vocabulary is emitted from a single state. A greedy, bottom-up method is then used to
  find the clustering; this method does not have a guarantee of finding the correct
  underlying clustering. In this paper we describe a new algorithm for clustering
  under the Brown et al. model. The method relies on two steps: first, the use of
  canonical correlation analysis to derive a low-dimensional representation of
  words; second, a bottom-up hierarchical clustering over these representations.
  We show that given a sufficient number of training examples sampled from the Brown
  et al. model, the method is guaranteed to recover the correct clustering. Experiments
  show that the method recovers clusters of comparable quality to the algorithm
  of Brown et al. (1992), but is an order of magnitude more efficient.'
title: A Spectral Algorithm for Learning Class-Based $n$-gram Models of Natural Language
year: '2014'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university14u
month: 0
tex_title: A Spectral Algorithm for Learning Class-Based $n$-gram Models of Natural
  Language
firstpage: 745
lastpage: 754
page: 745-754
order: 745
cycles: false
bibtex_author: University, Karl Stratos Columbia and Kim, Do-kyum and University,
  Daniel Hsu Columbia and University, Michael Collins Columbia
author:
- given: Karl Stratos Columbia
  family: University
- given: Do-kyum
  family: Kim
- given: Daniel Hsu Columbia
  family: University
- given: Michael Collins Columbia
  family: University
date: 2014-07-23
note: Reissued by PMLR on 04 October 2026.
address:
container-title: Proceedings of the 30th Conference on Uncertainty in Artificial Intelligence
volume: R12
genre: inproceedings
issued:
  date-parts:
  - 2014
  - 7
  - 23
pdf: https://raw.githubusercontent.com/mlresearch/r12/main/assets/university14u/university14u.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

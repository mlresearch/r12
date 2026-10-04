---
abstract: In this paper, we present a novel probabilistic la- bel enhancement model
  to tackle multi-label im- age classification problem. Recognizing multiple objects
  in images is a challenging problem due to label sparsity, appearance variations
  of the ob- jects and occlusions. We propose to tackle these difficulties from a
  novel perspective by construct- ing auxiliary labels in the output space. Our idea
  is to exploit label combinations to enrich the la- bel space and improve the label
  identification ca- pacity in the original label space. In particular, we identify
  a set of informative label combina- tion pairs by constructing a tree-structured
  graph in the label space using the maximum spanning tree algorithm, which naturally
  forms a condi- tional random field. We then use the produced label pairs as auxiliary
  new labels to augment the original labels and perform piecewise train- ing under
  the framework of conditional random fields. In the test phase, max-product message
  passing is used to perform efficient inference on the tree graph, which integrates
  the augmented label pair classifiers and the standard individual binary classifiers
  for multi-label prediction. We evaluate the proposed approach on several image classification
  datasets. The experimental results demonstrate the superiority of our label enhance-
  ment model in terms of both prediction perfor- mance and running time comparing
  to the-state- of-the-art multi-label learning methods.
title: Multi-label Image Classification with A Probabilistic Label Enhancement Model
year: '2014'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university14y
month: 0
tex_title: Multi-label Image Classification with A Probabilistic Label Enhancement
  Model
firstpage: 902
lastpage: 911
page: 902-911
order: 902
cycles: false
bibtex_author: University, Xin Li Temple and University, Feipeng Zhao Temple and University,
  Yuhong Guo Temple
author:
- given: Xin Li Temple
  family: University
- given: Feipeng Zhao Temple
  family: University
- given: Yuhong Guo Temple
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
pdf: https://raw.githubusercontent.com/mlresearch/r12/main/assets/university14y/university14y.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

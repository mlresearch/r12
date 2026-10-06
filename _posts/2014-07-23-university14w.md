---
abstract: Binary matrices and tensors are popular data structures that need to be
  efficiently approximated by low-rank representations. A standard approach is to
  minimize the logistic loss, well suited for binary data. In many cases, the number m of non-zero elements in the tensor is much smaller than the total number n
  of possible entries in the tensor. This creates a problem for large tensors because
  the computation of the logistic loss has a linear time complexity with n. In this
  work, we show that an alternative approach is to minimize the quadratic loss (root
  mean square error) which leads to algorithms with a training time complexity that
  is reduced from O(n) to O(m), as proposed earlier in the restricted case of alternating
  least-square algorithms. In addition, we propose and study a greedy algorithm
  that partitions the tensor into smaller tensors, each approximated by a quadratic
  upper bound. This technique provides a time-accuracy tradeoff between a fast but
  approximate algorithm and an accurate but slow algorithm. We show that this technique
  leads to a considerable speedup in learning of real world tensors.
title: Scalable Binary Tensor Factorization
year: '2014'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university14w
month: 0
tex_title: Scalable Binary Tensor Factorization
firstpage: 815
lastpage: 822
page: 815-822
order: 815
cycles: false
bibtex_author: University, Beyza Ermi\c{s} Bo\u{g}azi{\c{c}}i and Europe, Guillaume
  Bouchard Xerox Research Centre
author:
- given: Beyza Ermiş Boğaziçi
  family: University
- given: Guillaume Bouchard Xerox Research Centre
  family: Europe
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
pdf: https://raw.githubusercontent.com/mlresearch/r12/main/assets/university14w/university14w.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

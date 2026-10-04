---
abstract: Communication costs, resulting from synchro- nization requirements during
  learning, can greatly slow down many parallel machine learning algorithms. In this
  paper, we present a parallel Markov chain Monte Carlo (MCMC) algorithm in which
  subsets of data are pro- cessed independently, with very little com- munication.
  First, we arbitrarily partition data onto multiple machines. Then, on each machine,
  any classical MCMC method (e.g., Gibbs sampling) may be used to draw samples from
  a posterior distribution given the data subset. Finally, the samples from each ma-
  chine are combined to form samples from the full posterior. This embarrassingly
  parallel algorithm allows each machine to act inde- pendently on a subset of the
  data (without communication) until the final combination stage. We prove that our
  algorithm generates asymptotically exact samples and empirically demonstrate its
  ability to parallelize burn-in and sampling in several models.
title: Asymptotically Exact, Embarrassingly Parallel MCMC
year: '2014'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university14o
month: 0
tex_title: Asymptotically Exact, Embarrassingly Parallel {MCMC}
firstpage: 519
lastpage: 528
page: 519-528
order: 519
cycles: false
bibtex_author: University, Willie Neiswanger Carnegie Mellon and University, Eric
  Xing Carnegie Mellon and Wang, Chong
author:
- given: Willie Neiswanger Carnegie Mellon
  family: University
- given: Eric Xing Carnegie Mellon
  family: University
- given: Chong
  family: Wang
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
pdf: https://raw.githubusercontent.com/mlresearch/r12/main/assets/university14o/university14o.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

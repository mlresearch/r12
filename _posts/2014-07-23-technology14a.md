---
abstract: Recent approaches to causal discovery based on Boolean satisfiability solvers
  have opened new opportunities to consider search spaces for causal models with both
  feedback cycles and unmeasured confounders. However, the available methods have
  so far not been able to provide a principled account of how to handle conflicting
  constraints that arise from statistical variability. Here we present a new approach
  that preserves the versatility of Boolean constraint solving and attains a high
  accuracy despite the presence of statistical errors. We develop a new logical
  encoding of (in)dependence constraints that is both well suited for the domain and
  allows for faster solving. We represent this encoding in Answer Set Programming
  (ASP), and apply a state-of-the-art ASP solver for the optimization task. Based
  on different theoretical motivations, we explore a variety of methods to handle
  statistical errors. Our approach currently scales to cyclic latent variable models
  with up to seven observed variables and outperforms the available constraint-based methods in accuracy.
title: 'Constraint-based Causal Discovery: Conflict Resolution with Answer Set Programming'
year: '2014'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: technology14a
month: 0
tex_title: 'Constraint-based Causal Discovery: Conflict Resolution with Answer Set
  Programming'
firstpage: 27
lastpage: 36
page: 27-36
order: 27
cycles: false
bibtex_author: Technology, Antti Hyttinen California Institute of and Caltech, Frederick
  Eberhardt and Helsinki, Matti J{\"a}rvisalo HIIT/University of
author:
- given: Antti Hyttinen California Institute of
  family: Technology
- given: Frederick Eberhardt
  family: Caltech
- given: Matti Järvisalo HIIT/University of
  family: Helsinki
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
pdf: https://raw.githubusercontent.com/mlresearch/r12/main/assets/technology14a/technology14a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

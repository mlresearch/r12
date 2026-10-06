---
abstract: When belief propagation (BP) converges, it does so to a stationary point
  of the Bethe free energy F, and is often strikingly accurate. However, it may
  converge only to a local optimum or may not converge at all. An algorithm was recently
  introduced by Weller and Jebara for attractive binary pairwise MRFs which is guaranteed to return an $\epsilon$-approximation to the global minimum of F in polynomial
  time provided the maximum degree $\Delta$= O(log n), where n is the number of variables.
  Here we extend their approach and derive a new method based on analyzing first
  derivatives of F, which leads to much better performance and, for attractive models, yields a fully polynomial-time approximation scheme (FPTAS) without any degree
  restriction. Further, our methods apply to general (nonattractive) models, though
  with no polynomial time guarantee in this case, demonstrating that approximating
  log of the Bethe partition function, log ZB = -min F, for a general model to additive
  $\epsilon$-accuracy may be reduced to a discrete MAP inference problem. This allows
  the merits of the global Bethe optimum to be tested.
title: Approximating the Bethe Partition Function
year: '2014'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university14h
month: 0
tex_title: Approximating the {B}ethe Partition Function
firstpage: 264
lastpage: 273
page: 264-273
order: 264
cycles: false
bibtex_author: University, Adrian Weller Columbia and University, Tony Jebara Columbia
author:
- given: Adrian Weller Columbia
  family: University
- given: Tony Jebara Columbia
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
pdf: https://raw.githubusercontent.com/mlresearch/r12/main/assets/university14h/university14h.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

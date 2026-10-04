---
abstract: Markov chain Monte Carlo (MCMC) is a popular and successful general-purpose
  tool for Bayesian inference. However, MCMC cannot be practi- cally applied to large
  data sets because of the prohibitive cost of evaluating every likelihood term at
  every iteration. Here we present Fire- fly Monte Carlo (FlyMC) an auxiliary variable
  MCMC algorithm that only queries the likeli- hoods of a potentially small subset
  of the data at each iteration yet simulates from the exact pos- terior distribution,
  in contrast to recent propos- als that are approximate even in the asymptotic limit.
  FlyMC is compatible with a wide variety of modern MCMC algorithms, and only requires
  a lower bound on the per-datum likelihood fac- tors. In experiments, we find that
  FlyMC gen- erates samples from the posterior more than an order of magnitude faster
  than regular MCMC, opening up MCMC methods to larger datasets than were previously
  considered feasible.
title: 'Firefly Monte Carlo: Exact MCMC with Subsets of Data'
year: '2014'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university14e
month: 0
tex_title: 'Firefly {M}onte {C}arlo: Exact {MCMC} with Subsets of Data'
firstpage: 196
lastpage: 205
page: 196-205
order: 196
cycles: false
bibtex_author: University, Dougal Maclaurin Harvard and Harvard, Ryan Adams
author:
- given: Dougal Maclaurin Harvard
  family: University
- given: Ryan Adams
  family: Harvard
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
pdf: https://raw.githubusercontent.com/mlresearch/r12/main/assets/university14e/university14e.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

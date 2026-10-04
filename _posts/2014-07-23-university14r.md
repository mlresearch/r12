---
abstract: A popular approach for online decision making in large MDPs is time-bounded
  tree search. The effectiveness of tree search, however, is largely influenced by
  the action branching factor, which limits the search depth given a time bound. An
  obvious way to reduce action branching is to consider only a subset of potentially
  good ac- tions at each state as specified by a provided partial policy. In this
  work, we consider offline learning of such partial policies with the goal of speeding
  up search without significantly reduc- ing decision-making quality. Our first contribu-
  tion is to study learning algorithms based on re- ducing our learning problem to
  i.i.d. supervised learning. We give a reduction-style analysis of three such algorithms,
  each making different as- sumptions, which relates the supervised learning objectives
  to the sub-optimality of search using the learned partial policies. Our second contribu-
  tion is to describe concrete implementations of the algorithms within the popular
  framework of Monte-Carlo tree search. Finally, the third con- tribution is to evaluate
  the learning algorithms in two challenging MDPs with large action branch- ing factors,
  showing that the learned partial poli- cies can significantly improve the anytime
  per- formance of Monte-Carlo tree search.
title: Learning Partial Policies to Speedup MDP Tree Search
year: '2014'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university14r
month: 0
tex_title: Learning Partial Policies to Speedup {MDP} Tree Search
firstpage: 667
lastpage: 676
page: 667-676
order: 667
cycles: false
bibtex_author: University, Jervis Pinto Oregon State and University, Alan Fern Oregon
  State
author:
- given: Jervis Pinto Oregon State
  family: University
- given: Alan Fern Oregon State
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
pdf: https://raw.githubusercontent.com/mlresearch/r12/main/assets/university14r/university14r.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

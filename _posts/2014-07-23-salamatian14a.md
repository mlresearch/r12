---
abstract: We study the problem of a user who has both public and private data, and
  wants to release the public data, e.g. to a recommendation service, yet simultaneously
  wants to protect his private data from being inferred via big data analytics.
  This problem has previously been formulated as a convex optimization problem
  with linear constraints where the objective is to minimize the mutual information
  between the private and released data. This attractive formulation faces a challenge
  in practice because when the underlying alphabet of the user profile is large,
  there are too many potential ways to distort the original profile. We address this
  fundamental scalability challenge. We propose to generate sparse privacy-preserving
  mappings by recasting the problem as a sequence of linear programs and solving
  each of these incrementally using an adaptation of Dantzig- Wolfe decomposition.
  We evaluate our approach on several datasets and demonstrate that nearly optimal
  privacy-preserving mappings can be learned quickly even at scale.
title: 'SPPM: Sparse Privacy Preserving Mappings'
year: '2014'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: salamatian14a
month: 0
tex_title: "{SPPM}: Sparse Privacy Preserving Mappings"
firstpage: 618
lastpage: 627
page: 618-627
order: 618
cycles: false
bibtex_author: Salamatian, Salman and Technicolor, Nadia Fawaz and Labs, Branislav
  Kveton Technicolor and Technicolor, Nina Taft
author:
- given: Salman
  family: Salamatian
- given: Nadia Fawaz
  family: Technicolor
- given: Branislav Kveton Technicolor
  family: Labs
- given: Nina Taft
  family: Technicolor
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
pdf: https://raw.githubusercontent.com/mlresearch/r12/main/assets/salamatian14a/salamatian14a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

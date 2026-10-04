---
abstract: The existing work on densification of one permu- tation hashing [24] reduces
  the query processing cost of the (K, L)-parameterized Locality Sen- sitive Hashing
  (LSH) algorithm with minwise hashing, from O(dKL) to merely O(d + KL), where d is
  the number of nonzeros of the data vector, K is the number of hashes in each hash
  table, and L is the number of hash tables. While that is a substantial improvement,
  our analy- sis reveals that the existing densification scheme in [24] is sub-optimal.
  In particular, there is no enough randomness in that procedure, which af- fects
  its accuracy on very sparse datasets. In this paper, we provide a new densification
  pro- cedure which is provably better than the existing scheme [24]. This improvement
  is more signifi- cant for very sparse datasets which are common over the web. The
  improved technique has the same cost of O(d + KL) for query processing, thereby
  making it strictly preferable over the ex- isting procedure. Experimental evaluations
  on public datasets, in the task of hashing based near neighbor search, support our
  theoretical findings.
title: Improved Densification of One Permutation Hashing
year: '2014'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: university14s
month: 0
tex_title: Improved Densification of One Permutation Hashing
firstpage: 686
lastpage: 695
page: 686-695
order: 686
cycles: false
bibtex_author: University, Anshumali Shrivastava Cornell and University, Ping Li Rutgers
author:
- given: Anshumali Shrivastava Cornell
  family: University
- given: Ping Li Rutgers
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
pdf: https://raw.githubusercontent.com/mlresearch/r12/main/assets/university14s/university14s.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

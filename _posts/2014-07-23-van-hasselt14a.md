---
abstract: Van Seijen and Sutton (2014) recently proposed a new version of the linear
  TD($\lambda$) learning algo- rithm that is exactly equivalent to an online for-
  ward view and that empirically performed bet- ter than its classical counterpart
  in both predic- tion and control problems. However, their al- gorithm is restricted
  to on-policy learning. In the more general case of off-policy learning, in which
  the policy whose outcome is predicted and the policy used to generate data may be
  differ- ent, their algorithm cannot be applied. One rea- son for this is that the
  algorithm bootstraps and thus is subject to instability problems when func- tion
  approximation is used. A second reason true online TD($\lambda$) cannot be used
  for off-policy learning is that the off-policy case requires so- phisticated importance
  sampling in its eligibility traces. To address these limitations, we gener- alize
  their equivalence result and use this gen- eralization to construct the first online
  algorithm to be exactly equivalent to an off-policy forward view. We show this algorithm,
  named true on- line GTD($\lambda$), empirically outperforms GTD($\lambda$) (Maei,
  2011) which was derived from the same objective as our forward view but lacks the
  ex- act online equivalence. In the general theorem that allows us to derive this
  new algorithm, we encounter a new general eligibility-trace update.
title: Off-policy TD($ł$) with a true online equivalence
year: '2014'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: van-hasselt14a
month: 0
tex_title: Off-policy {TD}($ł$) with a true online equivalence
firstpage: 882
lastpage: 891
page: 882-891
order: 882
cycles: false
bibtex_author: Van Hasselt, Hado and Mahmood, Rupam and Sutton, Rich
author:
- given: Hado
  family: Van Hasselt
- given: Rupam
  family: Mahmood
- given: Rich
  family: Sutton
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
pdf: https://raw.githubusercontent.com/mlresearch/r12/main/assets/van-hasselt14a/van-hasselt14a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

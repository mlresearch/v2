---
title: A Unified Algorithmic Approach for Efficient Online Label Ranking
abstract: 'Label ranking is the task of ordering labels with respect to their relevance
  to an input instance. We describe a unified approach for the online label ranking
  task. We do so by casting the online learning problem as a game against a competitor
  who receives all the examples in advance and sets its label ranker to be the optimal
  solution of a constrained optimization problem. This optimization problem consists
  of two terms: the empirical label-ranking loss of the competitor and a complexity
  measure of the competitor’s ranking function. We then describe and analyze a framework
  for online label ranking that incrementally ascends the dual problem corresponding
  to the competitor’s optimization problem. The generality of our framework enables
  us to derive new online update schemes. In particular, we use the relative entropy
  as a complexity measure to derive efficient multiplicative algorithms for the label
  ranking task. Depending on the specific form of the instances, the multiplicative
  updates either have a closed form or can be calculated very efficiently by tailoring
  an interior point procedure to the label ranking task. We demonstrate the potential
  of our approach in a few experiments with email categorization tasks.'
pdf: http://proceedings.mlr.press/v2/shalev-shwartz07a/shalev-shwartz07a.pdf
layout: inproceedings
series: Proceedings of Machine Learning Research
id: shalev-shwartz07a
month: 0
tex_title: A Unified Algorithmic Approach for Efficient Online Label Ranking
firstpage: 452
lastpage: 459
page: 452-459
order: 452
cycles: false
author:
- given: Shai
  family: Shalev-Shwartz
- given: Yoram
  family: Singer
date: 2007-03-11
address: San Juan, Puerto Rico
publisher: PMLR
container-title: Proceedings of the Eleventh International Conference on Artificial
  Intelligence and Statistics
volume: '2'
genre: inproceedings
issued:
  date-parts:
  - 2007
  - 3
  - 11
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

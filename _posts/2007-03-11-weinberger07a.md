---
title: Metric Learning for Kernel Regression
abstract: Kernel regression is a well-established method for nonlinear regression
  in which the target value for a test point is estimated using a weighted average
  of the surrounding training samples. The weights are typically obtained by applying
  a distance-based kernel function to each of the samples, which presumes the existence
  of a well-defined distance metric. In this paper, we construct a novel algorithm
  for supervised metric learning, which learns a distance function by directly minimizing
  the leave-one-out regression error. We show that our algorithm makes kernel regression
  comparable with the state of the art on several benchmark datasets, and we provide
  efficient implementation details enabling application to datasets with  O(10k) instances.
  Further, we show that our algorithm can be viewed as a supervised variation of PCA
  and can be used for dimensionality reduction and high dimensional data visualization.
pdf: http://proceedings.pmlr.press/weinberger07a/weinberger07a.pdf
layout: inproceedings
id: weinberger07a
month: 0
firstpage: 612
lastpage: 619
page: 612-619
origpdf: http://jmlr.org/proceedings/papers/v2/weinberger07a/weinberger07a.pdf
sections: 
author:
- given: Kilian Q.
  family: Weinberger
- given: Gerald
  family: Tesauro
date: 2007-03-11
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

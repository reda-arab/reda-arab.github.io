---
title: 'Correlated features when doing Linear Regression : a geometrical approach'
date: 2022-03-04
permalink: /posts/2022/03/correlated_features_lr/
excerpt: Correlated features in Linear Regression <br/><img src='/images/corr.jpeg' style="width:220px;height:156px;">
tags:
  - Linear Regression
  - OLS
  - Orthogonal Projection
  - Coefficient estimates
  - Variance of an estimator
---

Goal of the document
======
This [document](https://reda-arab.github.io/files/Correlated features - Linear Regression.pdf) aims to give a geometrical approach of what is happening when two features are correlated when applying linear regression/OLS.
Indeed, we are investigating another way (formula) to compute the coefficient estimates which give us a new insight : we see directly that two highly correlated features improve the variance of the coefficient estimates associated.


Here is another [way](https://towardsdatascience.com/why-exclude-highly-correlated-features-when-building-regression-model-34d77a90ea8e) of seeing it, taking into account eigenvalues and SVD.


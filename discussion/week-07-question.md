---
id: w07-jacobjacobsonsq-cloud-qda-covariance-regularization
title: "When QDA's Flexibility Becomes Instability"
author: "Jacob Jacobson (jacobjacobsonsq-cloud)"
---

Suppose two classes truly have different covariance matrices, so the Bayes decision boundary is quadratic, but the number of predictors is large relative to the number of observations in each class. Ordinary QDA may then estimate the correct form of the boundary very noisily or fail because a within-class covariance matrix is singular. How should we decide whether to reduce dimension with PCA, regularize the class covariance matrices toward a pooled estimate, or use LDA instead? In particular, how do these choices trade bias against variance, and why must the dimension or regularization strength be selected entirely within cross-validation rather than by comparing performance on the final test set?

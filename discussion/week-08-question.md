---
id: w08-jacobjacobsonsq-cloud-cost-and-margin-errors
title: "When Does a Larger SVM Cost Hurt?"
author: "Jacob Jacobson (jacobjacobsonsq-cloud)"
---

In a linear SVM, increasing the cost parameter penalizes margin violations more heavily, so the fitted boundary may move to classify difficult training observations correctly and the margin may narrow. Suppose cross-validation error is nearly unchanged across a broad range of cost values, but the number and identities of the support vectors change substantially. What evidence would justify choosing a smaller cost rather than a larger one? In particular, how should we weigh margin width, the stability of the selected support vectors across folds, class-specific errors, and uncertainty in the cross-validation estimates when the mean error rates are almost tied?

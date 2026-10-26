---
id: w09-jacobjacobsonsq-cloud-selection-bias-in-svm-tuning
title: "When SVM Tuning Overfits Cross-Validation"
author: "Jacob Jacobson (jacobjacobsonsq-cloud)"
---

Suppose we use the same five folds to compare many combinations of SVM kernel, cost, degree, and radial scale, then report the smallest cross-validation error as the expected error of the selected model. Why is that reported minimum optimistically biased even though no observation was used to fit the model that predicted it? How should the number and spacing of candidate settings, the one-standard-error rule, repeated or nested cross-validation, and a final untouched test set affect model selection and the uncertainty we report?

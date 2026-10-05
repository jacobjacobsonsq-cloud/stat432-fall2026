---
id: w06-jacobjacobsonsq-cloud-auc-operating-region
title: "When Overall AUC Hides the Relevant Region"
author: "Jacob Jacobson (jacobjacobsonsq-cloud)"
---

Suppose two classifiers have nearly identical AUC values, but their ROC curves cross: model A is better when the false-positive rate must remain below 0.05, while model B is better elsewhere. If the application has a strict false-positive constraint and false negatives are much more costly than false positives within that feasible region, how should we compare the models and choose a cutoff? What additional information beyond overall AUC is needed to justify the final decision?

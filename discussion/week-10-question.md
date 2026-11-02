---
id: w10-jacobjacobsonsq-cloud-correlated-forest-importance
title: "When Correlated Predictors Split Importance"
author: "Jacob Jacobson (jacobjacobsonsq-cloud)"
---

Suppose a random forest contains one strong signal variable and nine nearly identical noisy copies of it, plus several independent predictors with weaker but genuine signals. Because each split sees only an `mtry` subset, the copies make the strong latent signal likely to be available even when any particular copy is absent, yet they can substitute for one another. How should we expect increasing `mtry` to affect prediction error, tree correlation, and permutation importance assigned to the copies and weaker predictors? In particular, why can each copy appear unimportant even when the latent signal is essential, and when would conditional or grouped permutation importance give a more faithful interpretation than ordinary marginal permutation importance? How should these importance measures be estimated without using the final test set?

---
id: w05-jacobjacobsonsq-cloud-redundant-measurement-distance
title: "When Repeated Measurements Dominate KNN Distance"
author: "Jacob Jacobson (jacobjacobsonsq-cloud)"
---

Suppose a response-relevant latent feature is recorded by ten highly correlated sensors, while a second, equally predictive latent feature is measured only once, and all eleven observed predictors are standardized before applying KNN. As the sensor noise approaches zero, how do the repeated measurements change Euclidean neighbor rankings even though they add almost no new predictive information? Could averaging the sensors, using PCA, using a Mahalanobis distance, or learning variable weights restore the intended balance without leaking test information, and under what conditions might each correction make prediction worse?

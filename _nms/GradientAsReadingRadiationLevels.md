---
title: Gradient as reading change in radiation levels
author: Thomas
Definition: We often minimize functions that have multiple inputs: $f : R^n  \rightarrow R$. For the concept of "minimization" to make sense, there must still be only one (scalar) output. For functions with multiple inputs, we must make use of the concept of partial derivatives. The partial derivative $f\frac{\partial}{\partial x_i}(x)$ measures how $f$ changes as only the variable $x_i$ increases at point $x$. The gradient generalizes the notion of derivative to the case where the derivative is with respect to a vector: the gradient of $f$ is the vector containing all the partial derivaties, denoted $\nabla_x f(x)$. Element $i$ of the gradient is the partial derivative of $f$ with respect to $x_i$
Description: We often have multiple sources of radiation that affect our readings. In order to know if we're in a safe zone, we simply want to know our radiation level as a single number. In order to do this, we can measure how the radiation changes if we only walk in one direction. We can then summarize this into a single reading for our current location (the gradient).
OriginSource: "Handmade"
Mapping:
  "Multi-dimensional dataset": "Multiple sources of radiation"
  "R^n -> R" : "Single reading"
  "Error / loss" : "Radiation"
  "Partial Derivative" : "Measure change in radiation for single direction"
  "Gradient" : "Summarize measurements into single reading for current locatio"
ExpertRating: Mediocre
---
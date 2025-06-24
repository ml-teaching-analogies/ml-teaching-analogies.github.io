---
title: Quadratic Discriminant Analysis as Classifying Different Athlete Types
author: mateo
Definition: Quadratic Discriminant Analysis is a variant of discriminant analysis that builds on the assumptions of multivariate normality but allows each class to have its own covariance matrix. This is in contrast to Linear Discriminant Analysis (LDA), which assumes an identical covariance structure across all classes. QDA’s ability to model differing class covariances makes it adept at handling real-world scenarios where variance is not homogeneous.
Description: You want to classify athletes into “low potential”, “medium potential”, and “high potential” based on their speed and endurance. It is easy to detect when someone has low potential but for a high potential there is way more variance. Quadratic Discriminant Analysis is a way to model each athlete when a simple rule like a straight line is not enough to differentiate them.
OriginSource: "Human plus ChatGPT 4o"
Mapping:
  "data point": "athletes"
  "feature vector": "speed and endurance"
  "class": "potential"
  "quadratic decision boundary": "different rules for speed and endurance"
ExpertRating: Bad
---
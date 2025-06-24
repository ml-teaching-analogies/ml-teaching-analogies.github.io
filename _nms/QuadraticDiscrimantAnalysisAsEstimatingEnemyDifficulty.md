---
title: Quadratic Discriminant Analysis as Estimating an Enemy's Difficulty
author: mateo
Definition: Quadratic Discriminant Analysis is a variant of discriminant analysis that builds on the assumptions of multivariate normality but allows each class to have its own covariance matrix. This is in contrast to Linear Discriminant Analysis (LDA), which assumes an identical covariance structure across all classes. QDA’s ability to model differing class covariances makes it adept at handling real-world scenarios where variance is not homogeneous.
Description: Imagine you are playing an action RPG game and want to estimate an enemy’s difficulty before fighting them. You can see their size, calmness, and complexity in design. If you want to separate them into “easy”, “medium”, and “hard” to defeat, you employ rules to separate them. You notice it’s easy to label when an enemy will be easy but it gets complicated to know when they are hard as there is a lot of variance in those enemies. Quadratic Discriminant Analysis is a way to model how difficult the enemy will be by applying curved boundaries to separate the groups.
OriginSource: "Human plus ChatGPT 4o"
Mapping:
  "data point": "enemy"
  "feature vector": "size, calmness, and complexity in design"
  "class": "difficulty"
  "quadratic decision boundary": "different rules for enemy's features"
ExpertRating: Bad
---
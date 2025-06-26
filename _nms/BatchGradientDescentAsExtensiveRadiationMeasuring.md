---
title: Batch Gradient Descent as doing extensive radiation measurements to find a safezone.
author: thomas
Definition: Note that the error function is defined with respect to a training set, and so each step requires that the entire training set be processed in order to evaluate ∇f(x). Techniques that use the whole data set at once are called batch methods.
Description: Our geiger counter takes measurements from its surroundings in order to calculate a direction that we need to move to. Batch gradient descent is like using all of our surroundings to calculate what direction we need to go to. This, of course, means our calculations are tied to how large our surroundings are. If our area grows, so does the time it takes to calculate the radiation and the direction we need to go into.
OriginSource: "Handmade"
Mapping:
  "Using entire dataset to calculate gradient.": "Using entirety of surroundings in order to measure direction"
  "Dataset size tied to computing speed" : "Size of surroundings tied to calculation time"
ExpertRating: Mediocre
---

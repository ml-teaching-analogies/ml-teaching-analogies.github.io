---
title: Discriminative vs Generative Classifiers as Classifying a Player Based on their Behaviour
author: mateo
Definition: Given a set of example data points, D, and their associated labels, L, a generative model learns the joint probability distribution P(D, L). It then uses this underlying distribution to generate new data similar to the training examples or address classification problems. Given a training dataset consisting of data points, D, and their associated labels, L, a discriminative model learns the conditional probability distribution P(D | L). It then uses this conditional probability distribution to predict the class of new data points.
Description: Imagine you have to guess someone’s profession by looking at them. Discriminative approach -> You know that anyone who has worn a tan suit works in marketing while someone with a black suit works in legal. Generative approach -> You try to think how someone who works in marketing dresses, acts, or walks. You check if your vision of a marketing employee matches the employee you see.
OriginSource: "Human plus ChatGPT 4o"
Mapping:
  "discriminative decision boundary": "color of suit"
  "generative distribution of features": "aspect and behaviour"
ExpertRating: Mediocre
---
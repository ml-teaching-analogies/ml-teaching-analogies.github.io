---
title: Discriminative vs Generative Classifiers as Guessing Someone's Profession
author: mateo
Definition: Given a set of example data points, D, and their associated labels, L, a generative model learns the joint probability distribution P(D, L). It then uses this underlying distribution to generate new data similar to the training examples or address classification problems. Given a training dataset consisting of data points, D, and their associated labels, L, a discriminative model learns the conditional probability distribution P(D | L). It then uses this conditional probability distribution to predict the class of new data points.
Description: 
Imagine you have to guess someone’s profession by looking at them.
- Discriminative approach -> You know that if a players tag starts with “xX” and ends with “Xx” they are a camper.
- Generative approach -> You know all about players' behaviours. You know what guns they use, how they move and where they tend to be. If a player keeps holding a corner with specific weapons you know they are likely a camper.
OriginSource: "Human plus ChatGPT 4o"
Mapping:
  "discriminative decision boundary": "tag of player"
  "generative distribution of features": "player's equipment and appearance"
ExpertRating: Mediocre
---
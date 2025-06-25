---
title: Cross-entropy as Horse Betting
author: ahmet
Definition: "Cross-entropy loss measures the difference between two probability distributions: the true labels and the model’s predicted probabilities. It is used for classification tasks. 1) For each data point, it calculates how far off the predicted probability is from the correct class. 2) It assigns a high penalty when the model is confident but wrong. 3) The loss is lowest when the model assigns high probability to the correct class."
Description: "You’re betting on a horse race with multiple horses. You don’t just pick one horse—you distribute your money (belief) across several based on how likely you think each will win. If the winning horse was the one you bet heavily on, you earn a lot. If you bet heavily on a horse that lost, you lose big."
OriginSource: ChatGPT 4o
Mapping:
  Each horse: A class label.
  The actual winning horse: The true label.
  Your bet distribution: The predicted probabilities over classes.
  Betting most of your money on the winner: Low cross-entropy loss (high confidence in the correct class).
  Betting on the wrong horse(s): High cross-entropy loss (high confidence in incorrect labels).
ExpertRating: Mediocre
---
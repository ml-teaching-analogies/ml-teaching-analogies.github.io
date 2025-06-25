---
title: Loglikelihood as detective
author: ahmet
Definition: "Log-likelihood measures how probable the observed data is under the model's predicted probability distribution. In classification: 1) The model predicts probabilities for each class. 2) The log-likelihood is the log of the probability assigned to the correct class. 3) The goal is to maximize this value, meaning the model is assigning high probability to the correct labels."
Description: "Imagine you’re a detective trying to identify the criminal from a group of suspects. You rank each suspect based on how likely you think they committed the crime. When the true criminal is near the top of your list (assigned high probability), you’re considered a good detective. If they’re low on your list, your performance is judged harshly."
OriginSource: ChatGPT 4o
Mapping:
  Each suspect: A possible class label
  The actual criminal: The true label
  Probability assigned to each suspect: The model's predicted class probabilities
  High rank (high probability) for the real criminal: Loglikelihood is high (loss is low)
  Low rank for the real criminal: Loglikelihood is low (loss is high)
  Penalizing bad rankings: Loglikelihood loss increases quickly when true label gets low predicted probability
ExpertRating: Good
---
---
title: Gaussian Naive Bayes Classifier as Recommending a Movie to a Friend
author: mateo
Definition: Gaussian Naive Bayes is a machine learning classification technique based on a probabilistic approach that assumes each class follows a normal distribution. It assumes each parameter has an independent capacity of predicting the output variable. It is able to predict the probability of a dependent variable to be classified in each group.
Description: You want to recommend a movie to a friend, you know the movie genre, main actor/actress and studio. These influence your friends opinion independently, Based on other movies you know they have liked before you estimate how much they will like this one.
OriginSource: "Human plus ChatGPT 4o"
Mapping:
  "data point": "movie"
  "features": "genre, cast, and studio"
  "class": "likes or dislikes"
  "class conditional probabilities": "feature preference based on past movies"
  "posterior probability": "what you predict will be liked"
ExpertRating: Mediocre
---
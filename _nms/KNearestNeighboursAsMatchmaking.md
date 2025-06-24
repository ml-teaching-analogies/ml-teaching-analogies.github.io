---
title: K Nearest Neighbours Classifier as Matchmaking in a Video Game
author: mateo
Definition: When you want to classify a data point into a category (like spam or not spam), the K-NN algorithm looks at the K closest points in the dataset. These closest points are called neighbors. The algorithm then looks at which category the neighbors belong to and picks the one that appears the most. This is called majority voting.
Description: To place a player in a matchmaking tier, it will look at the k nearest players with the most similar stats and put you in the most common tier among them.
OriginSource: "Human plus ChatGPT 4o"
Mapping:
  "feature vector": "player stats"
  "data point": "player"
  "class": "ranked tier"
  "nearest neighbours": "similar players"
  "prediction": "most common tier"
ExpertRating: Good
---
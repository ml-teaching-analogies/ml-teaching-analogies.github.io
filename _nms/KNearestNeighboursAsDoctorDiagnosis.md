---
title: K Nearest Neighbours Classifier as a Doctor Giving a Diagnosis
author: mateo
Definition: When you want to classify a data point into a category (like spam or not spam), the K-NN algorithm looks at the K closest points in the dataset. These closest points are called neighbors. The algorithm then looks at which category the neighbors belong to and picks the one that appears the most. This is called majority voting.
Description: A doctor wants to diagnose a patient with a given set of symptoms. The doctor looks at a database for k patients with the most similar symptoms and diagnoses the most common diagnosis among them.
OriginSource: "Human plus ChatGPT 4o"
Mapping:
  "feature vector": "symptoms"
  "data point": "patient"
  "class": "diagnosis"
  "nearest neighbours": "similar patients"
  "prediction": "most common diagnosis"
ExpertRating: Good
---
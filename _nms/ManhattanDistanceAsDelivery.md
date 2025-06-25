---
title: Manhattan Distance as Delivery
author: ahmet
Definition: "Manhattan distance is a way to measure how far two points are from each other by only moving along horizontal and vertical lines (like a grid). 1) You take the absolute difference between each predicted value and the actual value. 2) You sum up all those absolute differences"
Description: "Imagine you’re a delivery person in a city like Manhattan, where the streets are laid out in a perfect grid. You need to go from your location to the customer’s house. However, you can’t walk diagonally—only north/south or east/west along the streets. You try to minimize the total number of blocks you walk."
OriginSource: ChatGPT 4o
Mapping:
  Current location: Model’s prediction
  Destination (customer’s house): True value or label
  Blocks walked north/south/east/west: Absolute differences in each dimension.
  Total number of blocks walked: Manhattan distance = sum of absolute errors.
ExpertRating: Good
---
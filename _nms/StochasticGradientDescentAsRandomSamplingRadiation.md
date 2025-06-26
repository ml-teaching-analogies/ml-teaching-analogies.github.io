---
title: Stochastig Gradient Descent as sampling random radiation measurements to find a safezone.
author: thomas
Definition: The computational cost of calculating the gradient descent is O(m), where m is the training set size. As the training set size grows to billions of examples, the time to take a single gradient step becomes prohibitively long. The insight of SGD is that the gradient is an expectation. The expectation may be approximately estimated using a small set of samples. Speciﬁcally, on each step of the algorithm, we can sample a minibatch of examples drawn uniformly from the training set. The minibatch size m' is typically chosen to be a relatively small number of examples, ranging from one to a few hundred. Crucially, m' is usually held ﬁxed as the training set size m grows. We may ﬁt a training set with billions of examples using updates computed on only a hundred examples.
Description: We measure radiation based on our surroundings, so every measurement requires us to sample our surroundings. If we have a huge area to check, this would take a long time to process. However, if we configured our geiger counter to only (randomly) sample a couple of spots, we could still get useful measurements, meaning our time taken to measure stays consistent regardless of the area size that we're walking through. This also means that we don't fully measure all directions that we can walk in, meaning we might end up in a location that doesn't give us any safe direction to move in, even though there may be an even safer place somewhere else.
OriginSource: "Handmade"
Mapping:
  "Gradient descent is O(m)": "Huge area means longer processing time"
  "Minibatch" : "Randomly sample spots in our surroundings"
  "m' is fixed" : "Time to measure stays consistent, regardless of area size"
  "SGD can lead to stopping in local minima" : We end up in a safe location, but there may be a better on"
ExpertRating: Bad
---

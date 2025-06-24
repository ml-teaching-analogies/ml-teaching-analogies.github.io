---
title: Parzen Classifier as Overlapping WiFi Signals
author: mateo
Definition: Parzen classifier estimates probability density for each class using a non-parametric approach based on stored training examples. When computing output for a new observation, the contribution of each training example is integrated. The contribution is modeled by a kernel function and is influenced by the smoothing parameter (kernel width).
Description: You're in a mall surrounded by many overlapping Wi-Fi signals. Each store has hotspots. Your phone estimates your location based on the signal strength from each brand’s hotspots. The brand which has the strongest combined signal is likely where you are.
OriginSource: "Human plus ChatGPT 4o"
Mapping:
  "class": "store brand"
  "training data": "hotspots"
  "kernel influence": "signal strength"
  "density estimate": "overlapping signals"
  "classification": "strongest signal"
ExpertRating: Mediocre
---
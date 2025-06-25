---
title: Bias as Thermostat with an Adjustable Baseline
author: maria
Definition: Biases are essentially constants associated with each neuron. Unlike weights, biases are not connected to specific inputs but are added to the neuron's output. Biases serve as a form of offset or threshold, allowing neurons to activate even when the weighted sum of their inputs is not sufficient on its own. 
Description: "Imagine a thermostat-controlled heater in a house. The temperature sensor (like the inputs and weights) reads the room's temperature and decides whether to turn on the heater. However, there's also a baseline setting — a knob that allows you to set a desired minimum temperature. This knob doesn't depend on the sensor readings; it's always there, shifting the behavior of the system. That knob is like the bias in a neuron."
OriginSource: "ChatGPT 4o"
Mapping:
  "Neuron": "Thermostat"
  "Inputs": "Current room temperature"
  "Weights": "Sensitivity of thermostat to temperature"
  "Bias": "Thermostat baseline setting (minimum desired temperature)"
  "Weighted Sum": "Evaluation of temperature difference from target"
  "Output Activation": "Heater turning on or staying off"
  "Adaptability": "Changing the baseline setting"
ExpertRating: Good
---
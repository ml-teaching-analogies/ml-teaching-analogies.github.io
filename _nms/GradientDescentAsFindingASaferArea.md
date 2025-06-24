---
title: Gradient Descent as Finding a safe spot in an irratiated area.
author: Thomas
Definition: We can decrease $f$ by moving in the direction of the negative gradient. This is known as the method of steepest descent, or gradient descent. Steepest descent proposes a new point $x' = x - \epsilon \nabla_x f(x)$. Where $\epsilon$ is the learning rate, a positive scalar determining the size of the step.
Description: Gradient descent is like moving in the direction of a safer area, to a new spot. The new spot is chosen by walking in the direction of safety for some an amount of time that we decide beforehand. Once we arrive at a place with less radiation, we take a new measurement and decide on where to move next.
OriginSource: "Handmade"
Mapping:
  "updating x to x'": "Walking to a new spot"
  "Learning rate" : "Amount of time to walk in a direction"
  "Iterative property of gradient descent" : "Taking a new measurement"
ExpertRating: Mediocre
---
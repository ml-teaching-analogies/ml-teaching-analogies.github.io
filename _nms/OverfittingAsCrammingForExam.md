---
title: Overfitting as Cramming for an Exam
author: maria
Definition: Overfitting [...] occurs when a model learns to memorize the training data rather than generalize patterns from it, leading to poor performance on unseen data. Early stopping is a form of regularization that halts the training process when the performance of the model on a validation dataset starts to degrade. Instead of training the model until convergence, early stopping monitors the validation error during training and stops the training process when the validation error begins to increase.
Description: "Imagine a student preparing for an exam. If the student crams by memorizing exact answers from practice exams without understanding the material, they might do well on those practice tests but struggle with new questions on the real exam. This is like overfitting.  A wise teacher watches the student's progress and tells them to stop studying when they begin to show signs of mental fatigue and declining performance on mock exams — preventing burnout and poor generalization. This is like early stopping."
OriginSource: "ChatGPT 4o"
Mapping:
  "Training data": "Practice exam questions"
  "Model memorizing": "Student cramming exact answers"
  "Overfitting": "Student can't answer new/different questions"
  "Unseen data": "Real exam with new questions"
  "Validation dataset": "Mock exams during study "
  "Validation error": "Mistakes made on mock exams"
  "Early stopping": "Teacher stopping the student before burnout"
  "Convergence": "Studying until exhaustion"
ExpertRating: Good
---
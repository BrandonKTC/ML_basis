# Boosting Methods

WE CAN USE THEM WITH ANY MODELS (NOT JUST TREES)

- Boosting is not actually a machine learning algorithm, it's methodology applied to an existing machine learning algorithm, most commonly applied to the decision tree. and commonly know as Meta Learning.

- Implies that a combination of estimators with an applied coefficient could act as an effective ensemble estimator.

## AdaBoost (Adaptive Boosting)

weak learner: a weak model is a model that is too simple to perform well on its own.

works by using an ensemble of weak learners and then combine them through the use of a weighted sum, it adapts by using previously created weak learners in order to adjust misclassified instance for the next created weak learner.

- learn slowly in series

## Gradient 

gradient boosting is very similar to Adaboost, where weak learners are created in series in order to produce a strong ensemble model, it makes use of the residual error for learning.



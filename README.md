ML_basics

re-doing Machine Learning basics to be able to create powerful AI Producs

# Overfitting and Underfitting:

° Extreme bias or extreme variance both lead to bad models.
° we can visualize this effect by considering a model  that underfits (high bias) or a model that overfits (high variance).

## Overfits:
- the model fits too much to the noise from the data.
- often result in low error on training sets but high error on test/validation sets.

## Underfits:
- model doesn't capture the underlying trend of the data and doesn't fit the data well enough.
- low variance but high bias.
- often result of an excessively simple model.

about overfitting and underfitting, keep in mind the relationship of model performance on the training set vs the test/validation set.
when deciding optimal model complexity and wanting to fairly evaluate our model's performance we can consider both the train error and test error to select an ideal complexity

# Grid Search:
- Often more complex models have multiple adjustable hyperparameters.
- A grid search is a way of training and validating a model on every possible combination of multiple hyperparameter options.

# Cross Validation:

## Train | Test Split:
- Begin with entire data set.
- Split into two sets Train and Test.
- Train model then evaluate error on Test.
- Adjusting the hyperparameter base on base on the Error or performance from the test set.

## Train | Validation | Train Split:
- Begin with entire data set.
- Split into: Train, Validation, and Test.
- Set aside Test set for final metrics.
- Fit model on Train set, Evaluate performance on validation set.
- Adjust hyperparameter as needed.
- Final evaluation on the Test set, Do NOT adjust! Report this as final metric.
 
## cross_val_score:
- Begin with entire data set.
- Split into data Training and Test Data.
- Remove Test data for final evaluation.
- Choose K-Fold Split Value for Training Data ( larger K means more computation! ).
- Repeat for another combinations and another until you've seen all the data set.
- Use mean error for parameter adjustments.
- Get final metrics from final test set, Do NOT adjust! Report this as final metric.

## cross_validate:
cross_validate function allows us to view multiple performance metrics from cross validatioin on a model and explore how much time fitting and testing took.




ML_basics

re-doing Machine Learning basics to be able to create powerful AI Producs

Overfitting and Underfitting:

° Extreme bias or extreme variance both lead to bad models.
° we can visualize this effect by considering a model  that underfits (high bias) or a model that overfits (high variance).

Overfits:
- the model fits too much to the noise from the data.
- often result in low error on training sets but high error on test/validation sets.

Underfits:
- model doesn't capture the underlying trend of the data and doesn't fit the data well enough.
- low variance but high bias.
- often result of an excessively simple model.

about overfitting and underfitting, keep in mind the relationship of model performance on the training set vs the test/validation set.
when deciding optimal model complexity and wanting to fairly evaluate our model's performance we can consider both the train error and test error to select an ideal complexity

## Cross Validation:
give the ability to train on all the data and evaluate on all the data
- This is known as K-fold cross validation.
- Common choice for K is 10 so each test set is 10% of your total data.
- Largest K possible would be K equal to the number of rows

### fit():
- call simply calculates the necessary statistics
only call on the training data

### transform():
- call actually scales data and returns the new scaled version of data.

## Feature Scaling:
only scale the features not the label it can alter the definition of the target.
- improves the convergence of steepest descent algorithms, wich do not possess the property of scale invariance.
- if features are on different scales, certain weights may update faster than others since the feature values x(j) play a role in the weight updates.
Scaling the features so that their respective ranges are uniform is important in comparing measurements that have different units it allows us to directly compare model coefficients to each other.
- lead to great increases in performance.
- absolutely necessary for some models.
Standardization:
- Rescales data to have a mean (µ) of 0 and standard deviation (σ) of 1. (could have negative value)
Normalization:
Rescales all data values to be between 0-1.


## Regularization:
is a way to reduce model overfitting and variance
- requires additional bias.
- requires a search for optimal penalty hyperparameter.
Three types of Regularization:
* L1 Regularization:
adds a penalty equal to the absolute value of the magnitude of coefficients:
° Limits the size of the coefficients
° yield sparse models where some coef_ can become zero
- LASSO Regression
* L2 Regularization:
adds a penalty equal to the ^2 of the magnitude of coefficients:
° All coefficients are shrunk by the same factor.
° Doesn't necessarily eliminate coefficients
- Ridge Regression
* Combining L1 and L2:
combine L1 and L2 with the addition of an alpha parameter deciding the ratio between them
- Elastic Net

## Residuals:
- residual errors should be random and close to a normal distribution (on a kde plot (close to 0))
Residual plot shows residual arror vs. true y value:
- there should be no clear line or curve. (on the points)

# y = mx + b

Gradient Descent:
find the best Beta value to minimize the squared error.(b)

Cost Functions:
a "best-fit" line is define by minimizing the squared error.(m)

simple linear regression : include dealing with only 1 x feature and 1 y label to predict y hat.
linear regression deals with multiple (n) x features

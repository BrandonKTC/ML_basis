# Logistic Regression:
logistic regression is a CLASSIFICATION algorithm designed to predict categorical target labels.
It allow us to predict a categorical label based on historical feature data.
The categorical target column is two or more discrete class labels.

==Part One==

- Logistic Regression works by transforming a Linear Regression into a classification model through the use of the logistic function.
- Treat the y-axis as a probability of belonging to a class.
- Treating P(y=1) >= 0.5 as a cut-off for classification

==Part Two==

- Logistic function transforms any input to be between 0 and 1
- when we plug in the Linear Regression equation into the Logistic function it create a Logistic Regression
- Positive β indicates an increase in likelihood of belonging to 1 class with increase in associated x feature.
- Negative β indicates an decrease in likelihood of belonging to 1 class with increase in associated x feature.
- logistic regression uses Maximum Likelihood to find the best fitting model.

The odds of an event with probability ==p== is defined as the chance of the event happening divided by the chance of the event not happening

==Part Three==

- The first step for maximum likelihood is to go from log odds back to probability.
- Choose best coefficient values in log odds terms that creates maximum likelihood.
- In terms of cost function, we seek to minimize the log loss.

Likelihood = Product of probabilities of belonging to class 1.



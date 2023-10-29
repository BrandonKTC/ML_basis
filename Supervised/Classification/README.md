# Classification algorithms:
classification algorithms also often produce a probability prediction of belonging to a class:
- Class 0: 10% Probability
- Class 1: 85% Probability
- Class 2: 5% Probability

## ROC Curves:
Chart the True vs. False positives for various cut-offs for the ROC Curve.
By changing the cut-off limit, we can adjust True vs False Positives!
A perfect model would have a zero FP rate, Realistically with smaller data sets the ROC Curves are not as smooth.
- AUC - Area Under the Curve, allows us to compare ROCs for different models.

## Confusion Matrix:
- True Positive
* predicted categorie is the same as the actual categorie 1 row/1 column
- True Negative
* 2 row/ 2 column
- False Positive
* predicted categorie isn't the same as the actual categorie 1 row/ 2 column
- False Neagtive
* 2 row/ 1 column

## Accuracy:
How often is the model correct ? 
Formule : ( TP+TN ) / Total

## Recall:
When it actually is a positive case, how often is it correct ?
Formule : (TP) / Total Actual Positives

## Precision:
When prediction is positive, how often is it correct ?
Formule : (TP) / Total Predicted Positives

## F1-Score:
Is the harmonic mean of precision and recall.
Formule : ( 2 * precision * recall ) / ( precision + recall )


### MODELS:
- Logistic Regression


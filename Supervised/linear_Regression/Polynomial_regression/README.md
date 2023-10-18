# Polynomial Regression

will address for us:
- non-linear feature relationships to label
- interaction terms between features

## Non-linear relationships:
let's take for example a feature y that is not linear ( it's logarithmic ) if we ^2 this feature it become more linear and if we ^3 the feature it's become more linear and it's more easy to find beta coef_

## Interaction terms:
what if features are only significant when they are in sync with one another ? (synergie)
perhaps newspaper ad spend itself is not effective, but greatly increase effectiveness if added to a TV ad campaign.
- simplest way is to create a new feature that multiplies the two existing one together to create an (interaction term).
- we can keep the original features, and add on this the (interaction term).

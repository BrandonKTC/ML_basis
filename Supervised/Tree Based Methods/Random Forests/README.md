## decision tree is limited:
- Single feature for root node.
- Splitting criteria can lead to some features not being used.
- Potential for overfitting to data.

# Random Forests

Random forests have the ability to greatly increase the performance based on expanding ideas from the Decision Tree
. They are know as enseble learners, since they rely on an ensemble of models (multiple decision trees).

- create subsets of randomly picked features at each potential split

### Hyperparameters

for most of them they are the same as the decision tree

- Number of Estimators
How many decision trees to use total in forest ?
as we increase the number of estimator (decision trees) the error reduce, after a certain number of tree the error stagne.
- Number of Features
How many features to include in each subset when splitting at a node ?
start with a sqrt(N) (where N is the number of features) and adjust based on your specific dataset.
- Boostrap Samples
Allow for bootstrap sampling of each training subset of features ?
bootstrapping: a term used to describe "random sampling with replacement".
Recall for each split we are randomly selecting a subset of features, that helps create more diverse trees that are not correlated to each other.
it reduce correlation between trees, since trees are trained on different subsets of feature columns and data rows so that our model generalize better on unseen data
- Out-of-Bag Error
calculate OOB error during training ?
#### what is Bagging ?
Recall to actually use a Random Forest, we use bootstrapped data and then calculate a prediction based on the aggregated predition of the trees:
- Classification: Most Voted Y Class
- Regression: Average Predicted Ys

Out-of-Bag Samples:
they are the rows Not used for constructing some trees.we could use them to get performance test metrics on trees that did not use them

OOB is the error between the y_test and the OOB samples



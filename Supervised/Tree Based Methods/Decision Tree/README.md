# Decision Tree

## Nodes:
A decision node, represented by a square, shows a decision to be made.

### Root Node:
is at the very top of a tree

### Leaf (Terminal) Nodes:
They have no data going out of them (the data no longer split when we reach them).

## Splitting
It is a process of dividing a node into two or more sub-nodes whether the condition is True or False

## Pruning:
Pruning reduces the size of decision trees by removing parts of the tree that do not provide power to classify instances. Decision trees are the most susceptible out of all the machine learning algorithms to overfitting and effective pruning can reduce this likelihood.

# Gini Impurity
- Gini impurity is a mathematical measurement of how "pure" the information in a data set is. we can think of this as a measurement of class uniformity.

## Gini Impurity ( Classification )
- For a set of classes C for a given dataset Q, Pc is probability of class c.
G(Q) = ∑(C)Pc (1-Pc) : e.g (1/4)(1-1/4)

- if the goal of a decision tree is to separate out classes, we can use gini impurity to decide on data split values.
- we want to minimize gini impurity at leaf nodes (means we are separating classes effectively !)



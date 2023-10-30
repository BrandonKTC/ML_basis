# K Nearest Neighbors
it simply assigns a label to new data based on the distance between the old data and new data
- Choose K value.
- Sort feature vectors(N dimensional space)  by distance metric.
- Choose class based on K nearest feature vectors.

## KNN Considerations:
- Scaling is necessary for KNN.
-- Features could have vastly different value ranges

==How to choose the optimal K value==

* we want a K value that minimizes error

- Two Methods:
* Elbow method:
train a model with multiple K values on the same set of training points, then test them on the same test set and mark down the error rate for each K value

* Cross validate a grid searchof multiple K values and choose K that results in lowest error or highest accuracy 


## KNN for classification:
find the closest historical label point and assign it to the new label based on the number of K

## KNN Regressor:
can be used for regression tasks, it's performance can be quite poor and less efficient than other algorithms

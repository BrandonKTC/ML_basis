# Density Based Spatial Clustering of Applications with Noise

DBSCAN focuses on using density of points as its main factor for assigning cluster labels. This creates the ability to find cluster segmentations that other algorithms have difficulty with.

- DBSCAN iterates through points uses two key hyperparameters (epsilon and minimum number of points) to assign cluster labels.
- Unlike K-Means, it focuses on density as the main factor for cluster assignment of points.

### Epsilon:
Distance extended from a point to search for Min Number of Points.
### minimum number of points:
minimum number of points within epsilon distance to be a core point.

#### Adjusting these hyperparameters have two main outcomes:
- Changing number of clusters
- Changing what is an outlier point.

## DBSCAN Procedure:
- Pick a random point not yet assigned.
- Determine the point type
- Once a core point has been found, add all directly reachable points to the same cluster as core.
- Repeat until all points have been assigned to a luster or as an outlier.

## DBSCAN Point Types:

- Core
point with min. points in epsilon range. (often from the first random choosen point) 

- Border
in epsilon range of core point, but does not contain min. number of points.

- Outlier
Can not be "reached" by points in a cluster assignment.




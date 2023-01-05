## Iris_flower_K-means_clustering

### Libraries to Install
Numpy
Pandas
Matplotlib
SciKit-Learn


### K-means Cluster
This code is using the K-Means clustering algorithm to cluster the data in the iris_df DataFrame, which is assumed to have columns containing features that you want to cluster on.

The K-Means algorithm clusters the data into a specified number of clusters (in this case specified by the range(1, 11) loop). It starts with a specified number of initial centroids, which are randomly chosen data points from the data. It then assigns each data point to the closest centroid, and the centroids are moved to the mean position of their assigned data points. This process is repeated until the centroids stop moving or a maximum number of iterations is reached.

The 'elbow method' is being used here to determine the optimal number of clusters. The within-cluster sum of squares (WCSS) is plotted for each number of clusters, and the number of clusters where the change in WCSS begins to level off is considered the optimal number of clusters. This point is often referred to as the 'elbow' in the WCSS vs number of clusters plot.



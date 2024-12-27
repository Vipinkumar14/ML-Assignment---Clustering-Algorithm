# KMeans Clustering

**Description**: KMeans is an iterative clustering algorithm that partitions the dataset into K distinct clusters based on feature similarities. It works by:

1. Choosing K initial cluster centroids.
2. Assigning each data point to the nearest centroid.
3. Recalculating the centroids of each cluster.
4. Repeating steps 2-3 until convergence (when centroids no longer change).

### Why KMeans for Iris?
1. Iris dataset is well-suited for KMeans because:
2. It has clearly separable groups (species of Iris).
3. It's a low-dimensional dataset, so KMeans is efficient.

#  Hierarchical Clustering 
**Description**: Hierarchical clustering builds a tree-like structure (dendrogram) that represents the nested grouping of data. It works by:
1. Initially treating each data point as its own cluster.
2. Iteratively merging the closest clusters based on a distance metric.
3. The process stops when all points are in a single cluster or a predefined number of clusters is reached.
### Why Hierarchical for Iris?

1. It is suitable for Iris because:
2. It does not require the number of clusters to be predefined.
3. It allows us to visualize the hierarchy of clusters, which might reveal interesting structures in the data.

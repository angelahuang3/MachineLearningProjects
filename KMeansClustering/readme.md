K means clustering is an unsupervised learning algorithm (takes unlabeled data) that will attempt to **group similar clusters(data points) together** in your data.

e.g. cluster similar data

Objectives:

1. K-means aims to partition a dataset into k pre-defined number of clusters.
2. It groups data points(clusters) based on their similarity, typically measured by distance (e.g., Euclidean distance).
3. The goal is to minimize the within-cluster variance, meaning data points within a cluster should be as close to each other as possible.

\*\* Until clusters stop changing, repeat the following:<br>
  4. For each cluster, compute the cluster centroid by taking the mean vector of points in the cluster<br>
  5. Assign each data point to the cluster for which the centroid is the closest

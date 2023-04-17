# KMEANS Unsupervised Learning
This is a popular method of unsupervised learning used in clustering data points. The aim is to divide the points into a K cluster based on similarity where the value of K is a hyperparameter. This method works in an iterative format where the centroids of the clusters are updated until there is convergence in the algorithm.
Firstly, the Centroids are initialised randomly then in which the algorithm assigns each data point to the nearest centroid then after the first iteration, the algorithm recalculates the centroids of the clusters and reassigns the data points to the nearest centroid. This process is repeated until the centroids no longer change, or there is convergence. The algorithm tries to minimize the sum of squared distances between each data point and its assigned centroid during each iteration. 
Once there is convergence, the best K would be used to cluster the given data points.
## Application
The Kmeans can be used in various sectors such as:
- Image segmentation
- Anomaly detection
- Text or Image clustering
- Clustering of behaviours of customers etc

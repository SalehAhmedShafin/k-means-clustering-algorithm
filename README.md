# k-means-clustering-algorithm
Perform the k-means clustering algorithm applying Euclidean distance as a distance measure on the given dataset with k=2. And, Color the corresponding points on the clusters with different colors.

To accomplish the tasks you've mentioned, we'll need to read the data from a file, perform K-Means clustering, and then visualize the results. Let's break down the steps:

Read Data from File:

1- My data is stored in a data_k_mean.txt file where each row represents a data point, and each column represents a feature, i use the pandas library to read the data.

Perform K-Means Clustering:

2- I use manual the KMeans class code also you can use KMeans class from the sklearn.cluster module to perform K-Means clustering. We'll specify the number of clusters (k=2) and use the default Euclidean distance as the distance measure.

Visualization:

3- To visualize the results, I plot the data points and color them based on their cluster assignments.

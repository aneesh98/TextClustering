# TextClustering
Application of the K-Means clustering method on the movie plots to find out similar movies

## Dataset Used:
TMDB Box office prediction dataset. 

## Algorithm Used: Kmeans
K-Means is a clustering algorithm used to identify number of subgroups in data, such that each sub group has similar data points and data points in two different subgroup are different in nature. The no. of sub groups in K-means algorithm is fixed before iterating over the dataset. Thus we can have can try different no. of subgroups and see which one explains the data well. The data point is assigned to a cluster in such a way that the distance of the datapoint and the cluster centroid (The average value of all the datapoints in the same cluster) is minimized.

## Algorithm:
1) From the available data points initialize k (the prespecified number of clusters) random datapoints as initial cluster centers.
2) Recompute cluster centers
3) Keep iterating over the dataset, until the difference between the computed cluster centers of two consecutive iterations remains same or negligible.

Since 'k' the number of clusters is to be provided, we can find the optimal number clusters using two techniques:
1) Elbow curve method.
2) Silhoutte Score.

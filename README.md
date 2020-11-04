# PCA & KMeans Clustering & Agglomerative Clustering with Dendrogrograms

## US-Arrests-KMeans-Agglomerative-Dendrograms-
Using the US Arrests dataset applying EDA, PCA 2 clustering techniques - KMeans and Agglomerative Clustering with Dendogrograms to obtain a silhouette score. 

This dataset is a systematic approach for identifying and analyzing patterns and trends in crime.

The dataset contains statistics, in arrests per 100,000 residents for assault, murder, and rape in each of the 50 US states in 1973.

Also provided is the percent of the population living in urban areas.

## 1. KMeans

A Scree plot is a plot between WCSS (Within cluster sum of squares) and number of clusters. Without sound domain knowledge or in the scenarios with unclear motives, the scree plots help us decide the number of clusters to specify.

Using the Elbow method.

The Silhouette Score can be used to study the separation distance between the resulting clusters. The silhouette plot displays a measure of how close each point in one cluster is to points in the neighboring clusters and thus provides a way to assess parameters like number of clusters visually.https://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_silhouette_analysis.html#sphx-glr-auto-examples-cluster-plot-kmeans-silhouette-analysis-py


## 2. Dendrograms
A dendrogram contains two kinds of information. Firstly, it shows each merge that was performed. Secondly, the length of the vertical lines show the distances (Euclidean distance or whatever distance measure was specified) between the merged clusters

A) Average & Complete Linkage using Minkowski

B) Average & Complete Linkage using Euclidean


## Agglomerative Clustering
Selection of the Minkowski Average Dendrogram. 
Choose a fixed number of clusters based on the dendrogram of your choice. Run agglomerative hierarchical clustering with that number of clusters (and the linkage method and distance metric used for that dendrogram)

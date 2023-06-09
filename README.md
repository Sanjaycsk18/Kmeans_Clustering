# Kmeans_Clustering

## Overview 

 K-Means Clustering is an Unsupervised Learning algorithm, which groups the unlabeled dataset into different clusters. Here K defines the number of pre-defined clusters that need to be created in the process

## Algorithm
 •  Determines the best value for K center points or centroids by an iterative process.

 •  Assigns each data point to its closest k-center. Those data points which are near to the particular k-center, create a cluster

 ![image of Kmeans](https://serokell.io/files/q4/q49pm3tx.K-Means_Clustering_Algorithm_pic1_(1).png)

## Working of Kmeans Algorithm 

**Step-1**: Select the number K to decide the number of clusters.

**Step-2**: Select random K points or centroids. (It can be other from the input dataset).

**Step-3**: Assign each data point to their closest centroid, which will form the predefined K clusters.

**Step-4**: Calculate the variance and place a new centroid of each cluster.

**Step-5**: Repeat the third steps, which means reassign each datapoint to the new closest centroid of each cluster.

**Step-6**: If any reassignment occurs, then go to step-4 else go to FINISH.

**Step-7**: The model is ready.

## Choosing the value of "K number of clusters" in K-means Clustering:

## Elbow Method 
 
 The Elbow method is one of the most popular ways to find the optimal number of clusters. This method uses the concept of WCSS value. WCSS stands for Within Cluster Sum of Squares, which defines the total variations within a cluster. The formula to calculate the value of WCSS (for 3 clusters) is given below:
 
  WCSS= ∑P<sub>i</sub> <sub> in Cluster1</sub> distance(P<sub>i</sub> C<sub>1</sub>)² + ∑P<sub>i</sub> <sub>in Cluster2</sub> distance(P<sub>i</sub> C<sub>2</sub>)² + ∑P<sub>i</sub> <sub>in Cluster3</sub> distance(P<sub>i</sub> C<sub>3</sub>)²
  
  
   ![image of elbow method](https://media.geeksforgeeks.org/wp-content/uploads/20230418184509/download-(7).png)

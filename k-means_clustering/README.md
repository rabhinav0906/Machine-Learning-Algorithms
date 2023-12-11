K-means clustering is an unsupervised machine learning algorithm that partitions data into k clusters, minimizing intra-cluster distances and maximizing inter-cluster distances. 
Used for tasks like customer segmentation and image compression, it's simple, efficient, but sensitive to initial conditions, making it valuable for exploratory data analysis and pattern recognition.

This Python code snippet utilizes k-means clustering to analyze and categorize a Mall Customers dataset. 
It begins by importing necessary libraries, loading the dataset, and selecting relevant features—Annual Income and Spending Score. 
The elbow method is employed to find the optimal number of clusters by iteratively fitting k-means models and plotting the within-cluster sum of squares (WCSS) against the number of clusters. 
Based on the elbow method's insights, the code proceeds to train a k-means model with a chosen number of clusters (5 in this case). 
It then predicts cluster labels, visualizes the clusters, and highlights cluster centroids on a scatter plot. 
This clustering approach aids in customer segmentation, allowing businesses to understand distinct customer groups based on their spending behavior and annual income. 
The WCSS values are printed, offering insight into the clustering quality. 
The resulting plot provides a clear depiction of customer segments, aiding marketers and businesses in targeted strategies for different customer profiles.

![image](https://github.com/rabhinav0906/Machine-Learning-Algorithms/assets/141805520/58a2f9bf-d0d6-4555-88a0-17b71af6f09a)

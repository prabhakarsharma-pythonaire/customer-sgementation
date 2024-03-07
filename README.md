# customer-sgementation
This script conducts customer segmentation using K-means clustering on mall customer data, identifying clusters based on annual income and spending score. It utilizes k-means++ initialization for optimal convergence. Clusters are visualized and evaluated using the silhouette score.

Desciption-
This Python script performs customer segmentation analysis using the K-means clustering algorithm. The dataset used contains information about mall customers, including their annual income and spending score. The goal is to segment customers into distinct groups based on their purchasing behavior.

The script begins by importing necessary libraries such as NumPy, pandas, seaborn, and matplotlib. It then loads the dataset "Mall_Customers.csv" using pandas and performs exploratory data analysis to understand the distribution of gender, annual income, and age.

Next, it selects the "Annual Income" and "Spending Score" columns as features for clustering. The Within-Cluster-Sum-of-Squares (WCSS) method is used to determine the optimal number of clusters, and an elbow plot is generated to visualize the results.. 


The K-means clustering algorithm is applied with the optimal number of clusters, and cluster labels are assigned to each data point. The clusters are plotted on a scatter plot, with different colors representing each cluster and centroids marked.

Finally, the silhouette score is calculated to evaluate the quality of the clustering results, providing a measure of how well-defined the clusters are.

# Mall_Customer_Segmentation

This repository contains code to perform hierarchical clustering on customer data. Specifically, it:

1- Loads the required libraries like dplyr, cluster and factoextra

2- Imports the Mall_Customers.csv dataset and selects only the relevant columns

3- Scales the features using the scale() function

4- Uses a dendrogram to determine the optimal number of clusters, which is 5

5- Fits hierarchical clustering with the ward.D2 method and 5 clusters

6- Visualizes the clusters using factoextra, showing the clusters of customers on the scaled features of annual income and spending score

7- The end result is a clean clustering of the customers into 5 distinct groups based on their attributes.

This hierarchical clustering approach can be useful for customer segmentation to better understand and predict customer behavior. The code in this repository provides an example data science workflow using R to cluster customer data.

This repository contains code to perform hierarchical clustering on customer data. Specifically, it:

Loads the required R libraries for data manipulation (dplyr), clustering (cluster), and data visualization (factoextra)

Imports the Mall_Customers.csv dataset which contains customer demographic information and spending habits. The code selects the annual income and spending score columns to use as clustering features.

Scales the features (annual income and spending score) using the scale() function to standardize the range of values. This is an important pre-processing step for the clustering algorithm.

Uses a dendrogram (a tree-based representation of a hierarchical clustering solution) to visualize and determine the optimal number of clusters. Based on the elbow of the dendrogram, 5 clusters are selected.

Fits hierarchical clustering with the ward.D2 method and 5 clusters. Ward's method is used as it optimizes cluster membership by maximizing the between-cluster distances.

Visualizes the 5 clusters using factoextra, plotting the clusters of customers on the scaled features of annual income and spending score. This provides an insightful view of how the clustering algorithm grouped the customers.

The end result is a clean clustering of the customers into 5 distinct groups based on their demographic and spending attributes.

This hierarchical clustering approach can be useful for customer segmentation to better understand and predict customer behavior. The code in this repository provides an example data science workflow using R to cluster customer data. Please let me know if you have any questions or need any clarification!

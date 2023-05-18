# Mall_Customer_Segmentation

This repository contains code to perform hierarchical clustering on customer data. Specifically, it:

Loads the required libraries like dplyr, cluster and factoextra

Imports the Mall_Customers.csv dataset and selects only the relevant columns

Scales the features using the scale() function

Uses a dendrogram to determine the optimal number of clusters, which is 5

Fits hierarchical clustering with the ward.D2 method and 5 clusters

Visualizes the clusters using factoextra, showing the clusters of customers on the scaled features of annual income and spending score

The end result is a clean clustering of the customers into 5 distinct groups based on their attributes.

This hierarchical clustering approach can be useful for customer segmentation to better understand and predict customer behavior. The code in this repository provides an example data science workflow using R to cluster customer data.

Let me know if you have any other questions!

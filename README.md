# Mall_Customer_Segmentation


This hierarchical clustering approach can be useful for customer segmentation to better understand and predict customer behavior. The code in this repository provides an example data science workflow using R to cluster customer data.

This repository contains R code that performs hierarchical clustering on a dataset of mall customers based on their annual income and spending score. The code uses the hclust and clusplot functions to compute and visualize the clusters. The code also plots a dendrogram to help determine the optimal number of clusters.

The dataset contains 200 observations of 5 variables:

- CustomerID: A unique identifier for each customer

- Gender: The gender of the customer (Male or Female)

- Age: The age of the customer

- Annual Income (k$): The annual income of the customer in thousands of dollars

- Spending Score (1-100): A score assigned by the mall based on the customer’s spending behavior

The code can be run in any R environment that has the cluster package installed. The output is a two-dimensional plot that shows the clusters of customers and their characteristics.
This GitHub repository contains R code that performs hierarchical clustering on a dataset of mall customers based on their annual income and spending score. This code is designed to help businesses segment customers into distinct groups based on their spending behavior and annual income, allowing them to target their marketing and sales efforts more effectively.

1- The code first imports the dataset, which contains 200 observations of 5 variables including CustomerID, Gender, Age, Annual Income, and Spending Score. The code then uses the hclust and clusplot functions to compute and visualize the clusters of customers. 

2- To determine the optimal number of clusters, the code uses a dendrogram to visualize the distance between each pair of customers. The resulting dendrogram is plotted to help determine the optimal number of clusters. 

3- The code then fits hierarchical clustering to the dataset and assigns each customer to a cluster using the cutree function. Finally, the clusplot function is used to visualize the clusters of customers and their characteristics, including annual income and spending score.

4- This code is designed to be run in any R environment that has the cluster package installed. The output is a two-dimensional plot that shows the clusters of customers and their characteristics, allowing businesses to gain insights into customer behavior and preferences. 

Overall, this code provides a valuable tool for businesses looking to improve their marketing and sales strategies by segmenting customers and tailoring their approach to each group's unique characteristics.

This hierarchical clustering approach can be useful for customer segmentation to better understand and predict customer behavior. The code in this repository provides an example data science workflow using R to cluster customer data. Please let me know if you have any questions or need any clarification!

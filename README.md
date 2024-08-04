Project Overview:


Dataset:
Utilized the Mall Customer Segmentation dataset to analyze customer data.

Data Extraction:
Extracted and loaded the dataset from a zip file.

Data Preparation:
Selected key features: Age, Annual Income (k$), and Spending Score (1-100).
Scaled the features for improved clustering performance.

Determine Optimal Clusters:
Applied the Elbow Method to find the optimal number of clusters by plotting the Within-Cluster Sum of Square (WCSS).

Model Training:
Fitted a K-means clustering model with the determined number of clusters.
Added cluster labels to the dataset.

Results Visualization:
Visualized the clusters and centroids to understand the customer segments.

Save Results:
Saved the clustered data to a CSV file for further analysis.


Summary

The code performs the following steps:

Extract the dataset from a zip file.
Load and preview the data.
Select specific features and scale the data.
Determine the optimal number of clusters using the Elbow Method.
Fit the K-means model with the optimal number of clusters.
Add cluster labels to the DataFrame.
Visualize the clusters and centroids.
Save the clustered data to a CSV file.

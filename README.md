# Customer-Segmentation-KMeans
This project aims to segment customers based on their annual income and spending scores using the K-Means clustering algorithm. The insights from this segmentation can be used to tailor marketing strategies and improve business decisions.

Introduction
Customer segmentation is a crucial aspect of understanding and targeting different customer groups effectively. By analyzing customer behavior and demographic data, businesses can optimize their marketing strategies and enhance customer satisfaction.

Dataset
The dataset used in this project is the "Mall Customers" dataset, which includes the following features:

CustomerID: Unique identifier for each customer
Gender: Gender of the customer
Age: Age of the customer
Annual Income (k$): Annual income of the customer in thousand dollars
Spending Score (1-100): Score assigned by the mall based on customer spending behavior

Project Steps
Data Preprocessing: Loaded and preprocessed the data.
Feature Selection: Selected relevant features for clustering.
Clustering: Applied K-Means clustering to segment customers.
Visualization: Visualized the clusters and analyzed the characteristics of each cluster.
Analysis: Conducted detailed analysis to understand the demographics and spending behavior of each cluster.

Analysis
The analysis includes the following:

1. Summary Statistics
This chart shows the mean, median, and standard deviation for each cluster:
![meanmedianstd](https://github.com/user-attachments/assets/a5e4a22e-ea3f-4557-9cbb-b90a12b9d437)

This box plot shows the distribution of annual income by each cluster
![boxplot](https://github.com/user-attachments/assets/eb26c3af-8b67-4a26-bbed-027998fd48df)


The number of customers in each cluster:
![numberofcustomers](https://github.com/user-attachments/assets/d67d04bb-4b85-4b57-9ef9-c9d7a8c735f1)


4. Demographic Analysis
Gender Distribution:
![genderdistribution](https://github.com/user-attachments/assets/49311998-9ddc-4b6a-93a9-63312759f593)


6. Customer Profiles
 Cluster 0.0:
  Income - Mean: 55.30, Median: 54.00, Std: 8.99
  Spending - Mean: 49.52, Median: 50.00, Std: 6.53
  Age - Mean: 42.72, Median: 46.00, Std: 16.45

Cluster 1.0:
  Income - Mean: 86.54, Median: 79.00, Std: 16.31
  Spending - Mean: 82.13, Median: 83.00, Std: 9.36
  Age - Mean: 32.69, Median: 32.00, Std: 3.73

Cluster 2.0:
  Income - Mean: 25.73, Median: 24.50, Std: 7.57
  Spending - Mean: 79.36, Median: 77.00, Std: 10.50
  Age - Mean: 25.27, Median: 23.50, Std: 5.26

Cluster 3.0:
  Income - Mean: 88.20, Median: 85.00, Std: 16.40
  Spending - Mean: 17.11, Median: 16.00, Std: 9.95
  Age - Mean: 41.11, Median: 42.00, Std: 11.34

Cluster 4.0:
  Income - Mean: 26.30, Median: 25.00, Std: 7.89
  Spending - Mean: 20.91, Median: 17.00, Std: 13.02
  Age - Mean: 45.22, Median: 46.00, Std: 13.23

Cluster 0.0 Insights:
  High-income low spenders

Cluster 1.0 Insights:
  High-income high spenders

Cluster 2.0 Insights:
  Low-income high spenders

Cluster 3.0 Insights:
  High-income low spenders

Cluster 4.0 Insights:
  Low-income low spenders
  



This project was created using multiple python packages such as, pandas, matplotlib, and seaborn.
Datasets used: https://www.kaggle.com/datasets/nikhilchadha1537/mall-customers

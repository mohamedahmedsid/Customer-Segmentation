# Customer Segmentation with Unsupervised Learning

## Overview

This project applies unsupervised learning techniques to segment customers based on their ecommerce data. The goal is to identify distinct customer groups that can be targeted for marketing campaigns, product recommendations, and other business strategies.

## Problem Statement

Given a dataset containing ecommerce data for 1,000 customers, the objective is to determine the optimal number of customer segments using various clustering algorithms. The dataset does not provide any predefined clusters, so the task is to discover natural groupings within the data.

## Methodology

### 1. Data Exploration
   - **Understanding the Data**: Loaded and explored the dataset to understand the features and structure.
   - **Data Preprocessing**: Cleaned the data, handled missing values, and standardized the features to prepare for clustering.

### 2. Determining the Optimal Number of Clusters
   - **Elbow Method**: Applied the Elbow Method using K-Means clustering to suggest the optimal number of clusters.
   - **Silhouette Analysis**: Conducted Silhouette Analysis to validate the number of clusters determined by the Elbow Method.
   - **Hierarchical Clustering**: Performed Agglomerative Hierarchical Clustering to compare results and visualize the data structure using a dendrogram.

### 3. Clustering Algorithms
   - **K-Means Clustering**: Segmented the customers using K-Means and visualized the clusters.
   - **Hierarchical Clustering**: Segmented the customers using Agglomerative Clustering and compared the cluster formation with the K-Means results.
   - **Comparison and Interpretation**: Compared the results from different algorithms and interpreted the identified customer segments.

### 4. Results
   - The analysis revealed that `4` clusters were optimal based on the Elbow Method and Silhouette Analysis. These clusters were further validated with Hierarchical Clustering, showing consistency in the results across different methods.

### 5. Conclusion
   - The identified customer segments provide valuable insights for targeted marketing and personalized recommendations. The segmentation can help businesses tailor their strategies according to the characteristics of each customer group.

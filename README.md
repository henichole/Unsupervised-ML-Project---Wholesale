# machine_learning_project-unsupervised-learning
Wholesale Customer Segmentation Analysis

## Introduction
This project aims to uncover underlying patterns and segments from the 'Wholesale Data' dataset containing information about various products sold by a grocery store. Through unsupervised learning techniques such as KMeans and Hierarchical clustering, as well as dimensionality reduction with PCA, I want to understand customer behavior and strategize better targeting and service delivery.

## Part 1: Exploratory Data Analysis (EDA)
Objective: 
To understand the distribution and relationships of the dataset features.

Approach:
1. Imported and cleaned data, handling missing values and outliers.
2. Visualized the data using histograms, box plots, and scatter plots to understand the distributions and relationships.
3. Performed statistical analysis to gain insights into the data's central tendencies and variances.

Output Analysis:
1. Identified the range and scale of product spending across different categories.
2. Detected outliers that could potentially skew clustering algorithms.

Improvements:
Consider deeper outlier analysis to differentiate between anomalies and high-value customers.

## Part 2: KMeans Clustering
Objective: 
To segment customers into distinct groups based on their purchasing patterns.

Approach:
1. Used the Elbow Method to determine the optimal number of clusters.
2. Applied KMeans clustering and assigned cluster labels to each data point.

Output Analysis:
Clusters showed distinct purchasing behaviors which could represent different customer types.

Improvements:
Further analysis could be done to fine-tune the number of clusters and understand each cluster's profile.

## Part 3: Hierarchical Clustering
Objective: 
To provide an alternative segmentation of customers, highlighting the hierarchical structure in customer purchasing behavior.

Approach:
Conducted Hierarchical clustering and visualized it using a dendrogram.

Output Analysis:
The dendrogram provided a visual representation of customer groupings at different levels of similarity.

Improvements:
Adjusting the dendrogram's granularity and exploring different linkage methods could provide additional insights.

## Part 4: Principal Component Analysis (PCA)
Objective: 
To reduce the dataset's dimensionality while retaining most of the variance, facilitating easier visualization and analysis.

Approach:
1. Standardized the data and applied PCA.
2. Determined the number of components that explain 95% of the variance.

Output Analysis:
Reduced the dimensionality to seven principal components, simplifying the dataset and highlighting the most significant features.

Improvements:
Further analysis could be done on interpreting the principal components and their contribution to customer segmentation.




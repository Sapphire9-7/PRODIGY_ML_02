# PRODIGY_ML_02
Task 2 of the Prodigy InfoTech ML internship which involves clustering wine using the Kmeans clustering algorithm.
# Wine Data Clustering Project

This repository contains a data analysis and clustering project that focuses on the "Wine" dataset. The primary goal of this project is to perform data analysis, address outliers, scale the data, determine the optimal number of clusters, and build and evaluate a K-Means clustering model.

## File: WineClustering.ipynb

### Description
This Jupyter Notebook file is dedicated to the analysis and clustering of the Wine dataset. It outlines the steps taken to understand the data, address outliers, scale the features, and perform K-Means clustering with the ideal number of clusters.

### Steps:
1. Loaded the Wine dataset and obtained a comprehensive data description using the "ProfileReport" library.
2. Conducted statistical analysis on the dataset to gain insights into the data distribution and characteristics.
3. Addressed outliers in the dataset using the "Winsorization" technique to prevent them from negatively affecting the clustering results.
4. Scaled the features to ensure they have the same magnitude and prevent any feature from dominating the clustering process.
5. Utilized both the Within-Cluster Sum of Squares (WCSS) method and the silhouette method to identify the optimal number of clusters for K-Means clustering.
6. Built a K-Means clustering model using the best-fit number of clusters and evaluated the results.

This project showcases the application of clustering techniques to uncover hidden patterns and structures within the Wine dataset. The insights gained from this analysis can be valuable for various applications, including customer segmentation, quality control, and more.

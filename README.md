# Machine-Learning-Clustering-PCA-
## Overview
	This document outlines the analysis performed on two datasets: digital ads data for clustering and census data for PCA (Principal Component 	Analysis). The goal is to segment ads based on key performance metrics and to identify principal components that explain the most variance in the 	census data.
## Digital Ads Data Clustering
	Objective: 
		Segment types of ads based on CPM (Cost Per Mille), CPC (Cost Per Click), and CTR (Click Through Rate).
  ## Data Analysis Steps
	Data Import and Basic Analysis:
		Loaded the dataset and performed initial checks (head, tail, info, summary statistics).
	Missing Values Treatment:
		Imputed missing values for CPC, CTR, and CPM using defined formulas through a user-defined function.
	Outlier Detection:
		Identified outliers and discussed the necessity of treating them for K-Means clustering.
	Data Scaling:
		Applied z-score scaling to normalize data and improve algorithm performance.
	Clustering Analysis:
		Conducted hierarchical clustering using a dendrogram.
		Created an elbow plot to determine the optimal number of clusters for K-Means.
		Evaluated silhouette scores to confirm the optimal cluster count.
		Profiled ads based on identified clusters.
## PCA Analysis
	Objective: 
		Reduce dimensionality of census data while preserving variance.
	Key Steps:
		Created a covariance matrix and computed eigenvalues and eigenvectors.
		Identified the optimal number of principal components explaining at least 90% variance.
		Generated a scree plot to visualize explained variance by each principal component.
		Compared principal components with actual variables to identify significant contributors.
## Conclusion
	The analyses conducted provide valuable insights into digital marketing strategies and demographic trends from census data. These insights can guide 	strategic decisions aimed at optimizing ad campaigns and understanding population characteristics. This README file summarizes the objectives, 	methodologies, findings, and conclusions drawn from the analyses performed on the datasets provided. Adjustments can be made based on specific details 	or additional insights derived from your analysis.

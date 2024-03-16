# RiskClustering

# Fraud Detection Model with Clustering

This project implements a fraud detection model using user profile and transaction behavior data to categorize users into risk buckets. By applying clustering techniques, specifically KMeans, and utilizing the silhouette method to determine the optimal number of clusters, we aim to prioritize Anti-Money Laundering (AML) alerts more efficiently.

# Dataset
The expected dataset should include features such as transaction amount, transaction frequency, device and location information, payment method, transaction hour, user account age, and previous fraud reports.

# Methodology
Data Preprocessing: Standardize numeric features and encode categorical features.
Cluster Optimization: Utilize the silhouette method to determine the optimal number of clusters for KMeans.
Risk Bucketing: Apply KMeans clustering to categorize users into risk buckets and prioritize AML alerts for manual review.

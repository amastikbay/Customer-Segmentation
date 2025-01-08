# Customer Segmentation using Clustering

## Overview
This project does customer segmentation using clustering on a dataset of mall customers. By utilizing **K-Means** and **Hierarchical Clustering**, the customers are grouped into clusters based on their annual income and spending scores. This segmentation allows businesses to target specific customer groups more effectively.

## Features
- Data preprocessing and exploratory data analysis (EDA).
- Application of **K-Means Clustering** with optimal cluster selection using the Elbow Method.
- Implementation of **Hierarchical Clustering** with dendrogram visualization.
- Detailed cluster interpretation and visualization of results.

## Dataset
The dataset from Kaggle contains the following features:
- **CustomerID**: Unique identifier for each customer.
- **Gender**: Gender of the customer.
- **Age**: Age of the customer.
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars.
- **Spending Score (1-100)**: A score assigned by the mall based on customer spending behavior.

## Key Findings
1. Customers are grouped into clusters based on their income and spending habits:
   - High-income, high-spenders (premium target group).
   - Low-income, high-spenders (value-conscious customers).
   - High-income, low-spenders (conservative or selective customers).
   - Middle-income customers with balanced spending.
   - Low-income, low-spenders (budget-conscious customers).
2. Both **K-Means** and **Hierarchical Clustering** deliver meaningful segmentations that align with business needs.

## Requirements
To run the project, you will need the Python libraries that are used in the project

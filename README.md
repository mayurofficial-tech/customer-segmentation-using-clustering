# Customer Segmentation Using Unsupervised Machine Learning

## Project Overview

This project focuses on customer segmentation for a retail business (SmartCart) using unsupervised machine learning techniques.

The objective is to identify groups of customers with similar purchasing behavior, demographics, and spending patterns. These customer segments can help businesses design targeted marketing campaigns, improve customer retention, and increase sales.

---

## Business Problem

Retail businesses often have thousands of customers with different behaviors and preferences.

Treating every customer the same can reduce marketing effectiveness.

This project aims to:

* Identify distinct customer groups
* Understand spending patterns
* Analyze income and purchasing behavior
* Support personalized marketing strategies

---

## Dataset Features

The dataset includes customer information such as:

* Income
* Education
* Marital Status
* Customer Tenure
* Recency
* Product Spending Categories
* Number of Children
* Campaign Responses

---

## Project Workflow

### 1. Data Preprocessing

* Missing value treatment
* Data quality checks
* Data type conversion

### 2. Feature Engineering

Created new business-focused features:

* Age
* Customer Tenure
* Total Spending
* Total Children
* Living Status

### 3. Outlier Detection & Removal

* Income outlier treatment
* Age outlier treatment

### 4. Encoding

* One-Hot Encoding for categorical variables

### 5. Feature Scaling

* StandardScaler

### 6. Dimensionality Reduction

* Principal Component Analysis (PCA)
* 3D customer visualization

### 7. Clustering

#### K-Means Clustering

* Elbow Method
* Optimal K selection

#### Agglomerative Clustering

* Hierarchical customer grouping

### 8. Cluster Evaluation

* Silhouette Score
* Cluster comparison

### 9. Customer Segment Analysis

* Income patterns
* Spending behavior
* Cluster profiling

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* PCA
* K-Means
* Agglomerative Clustering
* Jupyter Notebook

---

## Project Structure

Customer-Segmentation/
│
├── smartcart.ipynb
├── smartcart_customers.csv
├── README.md
└── .gitignore

---

## Key Insights

* Identified distinct customer segments based on spending and demographics.
* Compared K-Means and Hierarchical Clustering techniques.
* Visualized clusters using PCA.
* Analyzed customer income and spending patterns.

---

## Future Improvements

* DBSCAN Clustering
* Gaussian Mixture Models (GMM)
* Interactive Dashboard using Streamlit
* Customer Recommendation System

---

## Skills Demonstrated

* Data Cleaning
* Feature Engineering
* Data Visualization
* PCA
* Unsupervised Learning
* Customer Segmentation
* K-Means Clustering
* Hierarchical Clustering
* Business Analytics

---

## Author

Mayur Makvana

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)(https://www.linkedin.com/in/mayurofficial-tech/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mayurofficial-tech)

Aspiring Data Analyst | Machine Learning Enthusiast

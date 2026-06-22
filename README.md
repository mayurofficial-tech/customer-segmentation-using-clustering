# Customer Segmentation Using Unsupervised Machine Learning

![Python](https://img.shields.io/badge/mayur-ram-blue?logo=<svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><title>Python</title><path d="M14.25.18l.9.2.73.26.59.3.45.32.34.34.25.34.16.33.1.3.04.26.02.2-.01.13V8.5l-.05.63-.13.55-.21.46-.26.38-.3.31-.33.25-.35.19-.35.14-.33.1-.3.07-.26.04-.21.02H8.77l-.69.05-.59.14-.5.22-.41.27-.33.32-.27.35-.2.36-.15.37-.1.35-.07.32-.04.27-.02.21v3.06H3.17l-.21-.03-.28-.07-.32-.12-.35-.18-.36-.26-.36-.36-.35-.46-.32-.59-.28-.73-.21-.88-.14-1.05-.05-1.23.06-1.22.16-1.04.24-.87.32-.71.36-.57.4-.44.42-.33.42-.24.4-.16.36-.1.32-.05.24-.01h.16l.06.01h8.16v-.83H6.18l-.01-2.75-.02-.37.05-.34.11-.31.17-.28.25-.26.31-.23.38-.2.44-.18.51-.15.58-.12.64-.1.71-.06.77-.04.84-.02 1.27.05zm-6.3 1.98l-.23.33-.08.41.08.41.23.34.33.22.41.09.41-.09.33-.22.23-.34.08-.41-.08-.41-.23-.33-.33-.22-.41-.09-.41.09zm13.09 3.95l.28.06.32.12.35.18.36.27.36.35.35.47.32.59.28.73.21.88.14 1.04.05 1.23-.06 1.23-.16 1.04-.24.86-.32.71-.36.57-.4.45-.42.33-.42.24-.4.16-.36.09-.32.05-.24.02-.16-.01h-8.22v.82h5.84l.01 2.76.02.36-.05.34-.11.31-.17.29-.25.25-.31.24-.38.2-.44.17-.51.15-.58.13-.64.09-.71.07-.77.04-.84.01-1.27-.04-1.07-.14-.9-.2-.73-.25-.59-.3-.45-.33-.34-.34-.25-.34-.16-.33-.1-.3-.04-.25-.02-.2.01-.13v-5.34l.05-.64.13-.54.21-.46.26-.38.3-.32.33-.24.35-.2.35-.14.33-.1.3-.06.26-.04.21-.02.13-.01h5.84l.69-.05.59-.14.5-.21.41-.28.33-.32.27-.35.2-.36.15-.36.1-.35.07-.32.04-.28.02-.21V6.07h2.09l.14.01zm-6.47 14.25l-.23.33-.08.41.08.41.23.33.33.23.41.08.41-.08.33-.23.23-.33.08-.41-.08-.41-.23-.33-.33-.23-.41-.08-.41.08z"/></svg>)

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)


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

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mayurofficial-tech/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mayurofficial-tech)

Aspiring Data Analyst | Machine Learning Enthusiast

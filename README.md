# K-Means Clustering on Telecom Customers

This repository contains a Jupyter Notebook that performs **K-Means clustering** on a telecom customer dataset to discover meaningful customer segments for business insights and strategy development.

## 📊 Project Overview

Customer segmentation is a powerful technique in customer analytics that allows businesses to identify groups of customers with similar behaviors. This project demonstrates how unsupervised learning — specifically K-Means clustering — can be used to classify customers into segments based on their usage patterns and demographics.

## 📁 Files

- `k-means-clustering-on-telecomcustomers.ipynb`: Main notebook that performs data preprocessing, EDA, clustering using K-Means, and cluster interpretation.
- `README.md`: Overview of the project, instructions, and background.

## 🔍 Key Steps Covered

- Data loading and exploration
- Preprocessing and normalization
- Elbow method to find optimal number of clusters
- K-Means clustering
- Cluster visualization and interpretation

## 📦 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`

## ⚙️ Methodology

- **Data Preprocessing**: Cleaned null values, standardized data, and performed encoding for categorical features.
- **Feature Selection**: Selected numerical features relevant to customer behavior.
- **Clustering**: Applied K-Means clustering with optimal `k` determined using the Elbow Method and Silhouette Score.
- **Visualization**: Used PCA and seaborn/matplotlib to plot customer clusters in 2D space.

## 📈 Results

Successfully segmented customers into distinct groups showing clear patterns in spending, contract types, and service usage. These clusters can assist with targeted marketing, churn reduction, and personalized service strategies.

## 📌 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/sarath1711/BDA.git
   cd BDA

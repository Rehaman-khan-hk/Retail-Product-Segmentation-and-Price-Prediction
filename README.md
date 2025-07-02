# 🛍️ Retail Product Segmentation and Price Prediction

This project involves **customer segmentation** using unsupervised learning (KMeans clustering) and **price prediction** using regression models. It leverages real-world e-shop data to help retailers make informed decisions about targeted marketing and pricing strategies.

## 📌 Overview

- **Goal**: Segment customers based on their purchasing behavior and predict product prices using key features.
- **Techniques Used**:
  - **KMeans Clustering** for unsupervised customer segmentation
  - **PCA (Principal Component Analysis)** for dimensionality reduction and visualization
  - **Exploratory Data Analysis (EDA)** to uncover trends and distributions
  - **Data Preprocessing** including normalization, encoding, and handling missing values
  - **Regression Modeling** (Linear Regression, XGBoost) for price prediction

## 📊 Dataset

The dataset includes:
- Customer demographics and purchasing behavior
- Product category and pricing
- Transaction history

> 📂 Dataset Source: [e-shop clothing retail dataset] (Insert source link here if public)

## 📈 Project Workflow

1. **Data Cleaning & Preprocessing**
   - Checked for nulls, duplicates, and outliers
   - Normalized continuous features
   - Encoded categorical data

2. **Segmentation with KMeans**
   - Applied elbow method and silhouette scores to find optimal cluster count
   - Reduced dimensions using PCA for 2D visualization
   - Visualized clusters using Seaborn scatter plots

3. **Price Prediction**
   - Selected features like brand, category, discount, and rating
   - Applied feature scaling and transformation
   - Trained multiple regression models; XGBoost performed best
   - Evaluated using RMSE and R² score

## 📊 Key Insights

- Customer segments revealed distinct purchase behavior based on spending and product preferences.
- Pricing was influenced most by brand, category, and discounts.
- XGBoost achieved the highest accuracy (~90% R² score) on the test set.

## 💻 Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## 📎 Visualizations

<p align="center">
  <img src="images/cluster_plot.png" width="500"/>
  <br/>
  <em>Customer Segmentation Clusters (PCA reduced)</em>
</p>

## 📁 Repository Structure


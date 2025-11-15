🧩 Customer Segmentation Using K-Means Clustering

📌 Project Overview

This project focuses on segmenting customers based on their purchasing behavior using K-Means clustering.
The goal is to group customers into meaningful segments so businesses can use targeted marketing strategies and improve customer satisfaction.

🎯 Objectives

Understand the structure of the customer dataset

Clean and preprocess the data

Choose important features for segmentation

Apply Elbow Method to find the correct number of clusters

Perform K-Means clustering (k=3)

Visualize customer segments

Generate business insights

🧹 1. Data Cleaning & Preparation

Steps completed:

Removed missing values

Removed duplicate records

Standardized column formats

Scaled numerical features using StandardScaler

Selected relevant features for clustering

🔍 2. Exploratory Data Analysis (EDA)

Performed:

Descriptive statistics

Distribution of customer spending

Relationship between income & spending

Outlier check

Feature understanding

📈 3. Model Building
Elbow Method

Used inertia (WCSS) to identify optimal K

Selected k = 3 clusters

K-Means Clustering

Performed clustering on scaled data

Assigned labels to each customer

🎨 4. Visualizations

Included charts:

Elbow curve

Scatter plot of clusters

Spending vs Income

Cluster comparison charts

Feature distributions

🛠️ Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-Learn

Jupyter Notebook / Google Colab

📁 Project Files

Customer_Segmentation.ipynb – full notebook

dataset.csv – customer data

README.md – project overview

📝 Key Insights

Identified 3 unique customer groups

High-income, high-spending group → premium customers

Moderate income & spending → target with offers

Low spending group → requires engagement strategies

Segmentation helps in planning marketing campaigns and personalized recommendations

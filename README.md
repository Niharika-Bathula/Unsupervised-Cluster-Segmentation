# Customer_segmentation


![image](https://github.com/Niharika-Bathula/Unsupervised-Cluster-Segmentation/assets/142409759/030222b6-8f9b-4e70-81e4-8f29e27801a4)



Clustering Analysis Performed on the Customers of a Mall based on some common attributes such as salary, buying habits, age and purchasing power etc, using Machine Learning Algorithms.

# Context
This data set is created only for the learning purpose of the customer segmentation concepts , also known as market basket analysis . I will demonstrate this by using unsupervised ML technique (KMeans Clustering Algorithm) in the simplest form.

# Content
You are owing a supermarket mall and through membership cards , you have some basic data about your customers like Customer ID, age, gender, annual income and spending score. Spending Score is something you assign to the customer based on your defined parameters like customer behavior and purchasing data.

Problem Statement You own the mall and want to understand the customers like who can be easily converge [Target Customers] so that the sense can be given to marketing team and plan the strategy accordingly.

# Dataset Overview
The dataset used in this project contains information about mall customers, including:

Customer ID
Gender
Age
Annual Income (in thousands of dollars)
Spending Score (1-100)

# Methodology

# Data Preprocessing:
Cleaning and preprocessing the dataset, handling missing values, and encoding categorical variables if necessary.

# Feature Selection: 
Selecting relevant features for clustering analysis, such as annual income and spending score.

# K-means Clustering:
Applying the K-means clustering algorithm to segment customers into distinct clusters based on their spending behavior.

# Evaluation:
Assessing the quality of clusters using metrics such as silhouette score and visual inspection of cluster centroids.

# Conclusion
By the end of this case study , you would be able to answer below questions. 1- How to achieve customer segmentation using machine learning algorithm (KMeans Clustering) in Python in simplest way. 2- Who are your target customers with whom you can start marketing strategy [easy to converse] 3- How the marketing strategy works in real world.

![image](https://github.com/Niharika-Bathula/Customer_segmentation/assets/142409759/81bd88fd-2edb-49db-99c6-fa82b937a109)

Utilized pandas and sklearn libraries for data manipulation and machine learning.

Renamed the 'Genre' column to 'Gender' for clarity and consistency. Visualized relationships between variables using various plots to gain insights into customer behavior and characteristics.

The analysis resulted in the identification of 5 distinct customer segments based on their spending behavior. Each segment exhibits unique characteristics and provides valuable insights for targeted marketing strategies and personalized customer experiences.

Employed KMeans algorithm for customer segmentation based on demographic and spending behavior. Utilized the elbow method to ascertain the optimal number of clusters, resulting in the determination of five clusters. 

Segmented customers into five distinct clusters (Cluster 1 to Cluster 5) based on features such as Age, Annual Income, and Spending Score.

This approach ensures effective customer segmentation based on the dataset's variance characteristics.

# Contributing
Contributions are welcome! For major changes, please open an issue first to discuss potential changes and improvements.

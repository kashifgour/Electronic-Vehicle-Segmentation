# Electric Vehicle Market Segmentation & Consumer Purchase Behavior Analysis

# Project Overview
This project focuses on market segmentation for electric vehicles (EVs) by applying various data processing and machine learning techniques. The goal is to predict different segments of EV data to better understand customer preferences and market trends.

# Data Pre-Processing

Data preprocessing is crucial for improving the quality of data and ensuring accurate results. The steps involved in preprocessing include:

- Handling Missing Values: Checking for and addressing missing values to avoid incorrect analysis.
- Removing Duplicates: Ensuring there are no duplicate records in the dataset.
- Identifying Outliers: Detecting and treating outliers that may distort the model's learning process.
- Data Encoding: Converting categorical data into a suitable numerical format for machine learning algorithms.

 # Techniques and Tools Used
The project employs various data visualization and preprocessing tools, including:

- NumPy and Pandas: For efficient data manipulation and analysis.
- Matplotlib and Seaborn: For creating insightful visualizations to understand data distribution and relationships.
- Categorical Encoding: Transforming categorical variables into numerical ones to make them suitable for machine learning models.
- Data Visualization
- Data visualization helps in identifying patterns, trends, and outliers in the dataset.
- 
 # Key visualizations include:
- KDE Plots: To visualize the probability density of continuous variables.
- Bar Plots: For comparing categorical data such as the number of seats or top speeds by brand.
- Pie Charts: To represent the distribution of different plug types used for charging.
- Histograms: For displaying the distribution of numerical data.
# Machine Learning Algorithms
Two clustering techniques were primarily used in this project to segment the electric car data:

- K-Means Clustering
K-Means clustering is a popular unsupervised learning algorithm used to partition data into k clusters. The steps involved are:

- Elbow Method: To determine the optimal number of clusters by plotting within-cluster sum of squares (WCSS) against the number of clusters.
- Cluster Visualization: To visualize the clusters formed and the centroids of these clusters.
- Hierarchical Clustering
Hierarchical clustering is another unsupervised learning technique that builds a hierarchy of clusters:

- Agglomerative Clustering: Merges data points into clusters based on their similarity.
- Dendrogram: A tree-like diagram that shows the arrangement of the clusters formed.
# Project Summary
The project showcases the application of various data processing and machine learning techniques to segment electric car data. By understanding different market segments, businesses can make informed decisions to cater to specific customer needs.

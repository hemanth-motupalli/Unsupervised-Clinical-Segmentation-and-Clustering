# Unsupervised Clinical Segmentation & Clustering

**Course:** IE507 - Modeling and Computation Lab  
**Institution:** IIT Bombay  

## Project Overview
This repository contains the implementation and analysis for two core data science tasks: unsupervised K-Means clustering on 2D spatial data, and comprehensive exploratory data analysis (EDA) using the Cleveland Heart Disease dataset. The objective is to apply clustering algorithms to segment data and utilize advanced visualization techniques to extract clinical correlations.

## Part 1: K-Means Clustering
* Implemented `scikit-learn` K-Means with the `k-means++` initializer to ensure optimal centroid placement.
* Tested and visualized cluster segmentations across a range of values ($K \in \{6, 7, 8, 9, 10, 11, 12, 13\}$).
* Established evaluation procedures using the Elbow Method (Within-Cluster Sum of Squares) and Silhouette Analysis to determine the mathematically optimal number of clusters.

## Part 2: Cleveland Heart Data Visualization
Performed EDA on 303 patient clinical records to identify hidden correlations among cardiovascular features.
* **Distribution Analysis:** Smoothed discrete age and serum cholesterol distributions using Kernel Density Estimates (KDE) to identify modality and skewness.
* **Categorical Segmentation:** Mapped categorical chest pain types (Typical Angina, Atypical Angina, Non-anginal, Asymptomatic) and evaluated median serum cholesterol differences across gender cohorts.
* **Statistical Visualization:** Utilized Box plots to map the Interquartile Range (IQR) and identify clinical outliers, and Violin plots to expose probability density variances hidden within standard quartile representations.

## Technologies Used
* **Languages:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
* **Environment:** Google Colab

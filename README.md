# Credit_Card_Customer_Segmentation

## Overview
This project aims to identify natural groupings within a dataset using unsupervised learning techniques for customer segmentation. By performing clustering, we can better understand customer behaviors, spending patterns, and financial profiles.

## Features & Technologies Used
### Libraries: 
Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Kneed

### Clustering Algorithms:
K-Means
DBSCAN (Density-Based Spatial Clustering)
Gaussian Mixture Model (GMM)
Hierarchical Clustering (HCA)
Dimensionality Reduction: Principal Component Analysis (PCA)

### Evaluation Metrics: 
Silhouette Score, Davies-Bouldin Index

## Installation
To run this project, install the required dependencies:

bash
pip install -r requirements.txt

Or install individual libraries:

bash
pip install numpy pandas scikit-learn matplotlib seaborn kneed

## Data Preprocessing
### Handling Missing Values: 
Used iterative imputation techniques.

### Feature Engineering: 
Removed highly correlated features to improve clustering.

### Standardization: 
Applied StandardScaler to normalize dataset for PCA.

### Dimensionality Reduction: 
Retained six principal components.

## Clustering Approach
Determined the optimal number of clusters using the Elbow method.
Applied different clustering techniques and compared their results using Silhouette Score.
Visualized clustering results using scatter plots and heatmaps.

## Results
Best Performing Algorithm: K-Means clustering achieved a Silhouette Score of 0.32.
DBSCAN struggled due to lack of distinct clusters.
GMM had a low silhouette score (0.08), indicating weak separation.
HCA showed overlapping clusters but was useful for hierarchical patterns.


## Future Improvements
Tune hyperparameters for DBSCAN to handle outliers.
Explore additional feature selection techniques for better clustering performance.
Improve cluster interpretability using domain-specific insights.

## Data Source
The dataset used in this project is sourced from **Kaggle**. You can find it here: [Customer_Data_Kaggle](<https://www.kaggle.com/code/maralka/clustering-credit-card-customers/input>)

## Contributors
Bhabilsh Limbu - BSc Computer Science (Data Science) 

## How to Run
Execute the program to perform clustering analysis on the dataset 'Customer_Data_kaggle'

## License
This project is licensed under the Apache 2.0

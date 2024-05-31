# IdentifyingHighNeedCountriesforAidUsingPCAandClusteringAlgorithms
![Alt text](https://github.com/yourusername/yourrepository/raw/branchname/path/to/your/image.png)
![Alt text](https://github.com/yourusername/yourrepository/raw/branchname/path/to/your/image.png)
![Alt text](https://github.com/yourusername/yourrepository/raw/branchname/path/to/your/image.png)
![Alt text](https://github.com/yourusername/yourrepository/raw/branchname/path/to/your/image.png)

## Project Overview
This project aims to strategically allocate $120 million in humanitarian aid by identifying countries in dire need using advanced data science techniques. By analyzing socio-economic and health indicators, we employ Principal Component Analysis (PCA), K-Means Clustering, and Hierarchical Clustering to classify and prioritize countries, ensuring that aid reaches those who need it most.

## Project Objectives
1.Normalize and preprocess data: Ensure data consistency and handle missing values.
2.Dimensionality reduction with PCA: Reduce the complexity of the dataset while retaining critical information.
3.Cluster countries using K-Means: Group countries based on socio-economic and health factors.
4.Hierarchical clustering: Validate and compare clustering results.
5.Identify priority countries: Recommend countries for aid allocation based on clustering results.

## Methodology
1.Data Preprocessing
Load and inspect data: Read the dataset and check for any inconsistencies or missing values.
Handle missing values: Impute missing values using the median of the respective columns.
Normalize the data: Use Min-Max Scaling to bring all feature values to a common scale.
2.Principal Component Analysis (PCA)
Dimensionality reduction: Apply PCA to reduce the number of features while retaining 90% of the variance.
Explained variance: Visualize the cumulative explained variance to determine the number of principal components.
3.K-Means Clustering
Elbow method: Determine the optimal number of clusters.
Clustering: Apply K-Means clustering to group countries and analyze cluster characteristics.
4.Hierarchical Clustering
Dendrogram: Create a dendrogram to visualize the hierarchical clustering.
Agglomerative clustering: Fit agglomerative clustering and compare results with K-Means.
5.Cluster Analysis and Recommendations
Cluster summary: Analyze the socio-economic and health indicators of each cluster.
Priority identification: Identify and recommend countries in the highest priority cluster for aid allocation.
Results and Findings
Principal Component Analysis: Successfully reduced dimensionality while retaining significant variance.
K-Means Clustering: Identified optimal clusters and grouped countries based on their socio-economic and health factors.
Hierarchical Clustering: Validated and compared with K-Means results, confirming the clustering structure.
Priority Countries: Recommended countries in the highest priority cluster for aid allocation.

## Contact
For any questions or suggestions, please contact Arsh Zehra at zehrarsh@gmail.com.

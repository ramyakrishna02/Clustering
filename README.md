# Clustering
Clustering is a technique in machine learning that groups similar data points together based on their characteristics. It is an unsupervised learning method that relies on finding similarities between data points without any prior knowledge of the data set. 

Clustering can be used for market segmentation, social network analysis, search result grouping, medical imaging, image segmentation, and anomaly detection among other applications.


### Hierarchical Clustering:

Hierarchical clustering is an unsupervised machine learning algorithm that is used to group unlabeled datasets into a cluster. It is also known as hierarchical cluster analysis or HCA. 
In this algorithm, we develop the hierarchy of clusters in the form of a tree, and this tree-shaped structure is known as the dendrogram. 

The hierarchical clustering technique has two approaches: 
Agglomerative and Divisive


### K-Means Clustering:

K-Means clustering is a method used for clustering analysis, especially in data mining and statistics. It aims to partition a set of observations into a number of clusters (k), resulting in the partitioning of the data into Voronoi cells. It can be considered a method of finding out which group a certain object really belongs to. 

The method starts by randomly selecting k initial centroids, then assigns each observation to the nearest centroid. After that, it calculates the new centroid for each cluster as the mean of all observations assigned to it. The algorithm repeats these steps until the centroids no longer move.


### DBSCAN Clustering:

DBSCAN stands for Density-Based Spatial Clustering of Applications with Noise. 

It is a density-based clustering algorithm that groups together points that are close to each other based on a distance measurement and a minimum number of points. The algorithm increases regions with sufficiently high density into clusters and finds clusters of arbitrary architecture in spatial databases with noise. It represents a cluster as a maximum group of density-connected points

## Implementation
- Importing the required Libraries and Reading the dataset
- Performing EDA (Exploratory Data Analysis) on the data
  Performing the following Types of Clustering:
- Hierarchical Clustering
  - Normalizing the data
  - Creating Dendrogram structure
  - Creating Hierarchical cluster
  - Draw inferences
- K-Means Clustering
  - Normalization of the data
  - Plotting Elbow Curve for K value
  - Creating K-Means cluster
  - Draw inferences
- DBSCAN Clustering
  - Normalizing the data
  - Plotting Elbow Curve for Epsilon (eps) value
  - Creating DBSCAN cluster
  - Draw inferences
- Comparison and Conclusions.

## Packages Used
- pandas
- numpy
- matplotlib.pyplot
- seaborn
- from sklearn.cluster import AgglomerativeClustering
- from sklearn.cluster import KMeans
- from sklearn.cluster import DBSCAN
- from sklearn.preprocessing import MinMaxScaler
- from scipy.cluster.hierarchy import linkage
- import scipy.cluster.hierarchy as sch

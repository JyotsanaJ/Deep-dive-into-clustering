## Clustering Techniques with Scikit-Learn
=======================================

This repository explores various types of clustering algorithms and implements them using scikit-learn in Jupyter notebooks. Clustering is an unsupervised learning technique used to group similar data points together based on their features. These notebooks serve as a comprehensive guide to understanding and applying different clustering methods.

### Clustering Techniques Covered
-----------------------------

1.  **K-Means Clustering**
    
    *   K-Means is one of the most widely used clustering algorithms. It partitions the data into K clusters by iteratively assigning each data point to the nearest cluster centroid and updating the centroids based on the mean of the points in the cluster.
    
2.  **Hierarchical Clustering**
    
    *   Hierarchical clustering builds a hierarchy of clusters by either merging smaller clusters into larger ones (agglomerative) or splitting larger clusters into smaller ones (divisive). It does not require specifying the number of clusters beforehand.
    
3.  **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**
    
    *   DBSCAN is a density-based clustering algorithm that groups together closely packed points and identifies outliers as noise. It does not require specifying the number of clusters and is robust to noise and outliers.
    
4.  **Gaussian Mixture Models (GMM)**
    
    *   GMM assumes that the data is generated from a mixture of several Gaussian distributions and assigns probabilities to each point belonging to each cluster. It is capable of identifying complex clusters with non-linear boundaries.
    

### Requirements
------------

*   Python 3.x
*   Jupyter Notebook
*   NumPy
*   Matplotlib
*   Scikit-learn

Install the required dependencies using pip:

```
pip install jupyter numpy matplotlib scikit-learn
```


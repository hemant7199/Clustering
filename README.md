# Clustering Algorithm Comparison

This project compares four clustering algorithms using the PyCaret library. The algorithms compared are:
- K-means
- Agglomerative Clustering
- Birch Clustering
- Spectral Clustering

## Number of Clusters
The algorithms are compared using the following number of clusters:
- 3 clusters
- 4 clusters
- 5 clusters
- 6 clusters

## Pre-processing Techniques
The following pre-processing techniques are applied to the dataset:
1. No pre-processing
2. Normalization
3. Transformation
4. PCA (Principal Component Analysis)
5. Transformation and Normalization
6. Transformation, Normalization, and PCA

## Libraries Used
- PyCaret
- Pandas

## Dataset
The dataset used for clustering is `seeds.csv`.

## Steps
1. Import necessary libraries.
2. Load the dataset.
3. Apply different pre-processing techniques.
4. Train and compare the clustering algorithms using different numbers of clusters.
5. Evaluate and visualize the results.

## Results
The results of the clustering algorithms are compared based on different pre-processing techniques and the number of clusters.

## Conclusion
This project provides insights into how different clustering algorithms perform under various pre-processing techniques and cluster numbers.

## Usage
To run the project, execute the Jupyter notebook `Clustering.ipynb`.

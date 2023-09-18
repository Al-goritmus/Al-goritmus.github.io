---
layout: post
title: "Clustering and PCA for client segmentation \n
[Business intelligence with Machine Learning algorithms]"
subtitle: "Clustering using Python-Scikit-learn, then PCA for feature importances"
background: '/img/posts/elbow.png'
---

## Segmentation project using clustering and PCA

### This project aims to segmentate clients using K-means for clustering, then PCA for feature importances

Remember that PCA is a linear algebra based strategy that aims to reduce dimensionality using a covariance matrix, in order to obtain the Eigenvectors and eigenvalues, eigenvectors are in simple terms, the directions in which the data varies the most, each eigenvector is perpendicular (or "orthogonal") to the others, which means they're linearly independent allow to rotate the vectorial space and eigenvalues represent the amount of variance from each eigenvector. Here we reduce dimensionality from a segmentation proyect where we worked with over 40 features, then this code allows to reduce dimensionality retaining variance, in other words to eliminate highly correlated variables, also we can then extract the weights or feature importance for each feature to the principal components, this is to use linear algebra in a very smart way.

### main_functions.

1)KNN imputer

2)K-means algorithm 

3)Elbow method for determining optimal number of clusters

![elbow_code](\img\posts\elbow_code.png)

4)Clustering for 3 most optimal n of clusters

5)Metrics using Silhouette score and WCSS

7)PCA for finding feature importances

![pca_code](\img\posts\pca_code.png)

 [git_hub link to project repository](https://github.com/Al-goritmus/clustering)

#### note: 
This code is made for trying different methods of imputing, then different numbers of clusters, then different metrics and then PCA.

![PCA_feature_importance](\img\posts\pca.png)

![PCA](\img\posts\pca2.png)
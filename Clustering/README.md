# Clustering

This directory contains a python implementation of a [k-means clustering algorithm](https://en.wikipedia.org/wiki/K-means_clustering) and a [spectral clustering algortihm](https://en.wikipedia.org/wiki/Spectral_clustering).

The notebook k-means-implementation.ipynb contains a k-means algorithm to compress images based on different values of k (different cluster sizes). It is a python implementation and makes use of numpy and scipy for vectorized calculations, particularly for calculating pixel "distance" in the context of the k-means algorithm.

The notebook spectral-clustering.ipynb contains a python implementation of the spectral clustering algorithm. As written, the algorithm is for clustering of data in a graph data structure with a nodes and edges file. This notebook also contains an example of how to do a basic eigendecomposition on an adjacency matrix.

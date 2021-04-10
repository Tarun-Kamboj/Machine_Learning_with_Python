# Hierarchical Clustering

![](http://ForTheBadge.com/images/badges/made-with-python.svg) 

## Dependencies

![](https://img.shields.io/badge/pandas-1.2.3-150458?style=for-the-badge&logo=pandas)
![](https://img.shields.io/badge/numpy-1.19.2-013243?style=for-the-badge&logo=NumPy)
![](https://img.shields.io/badge/matplotlib-3.3.4-224099?style=for-the-badge)
![](https://img.shields.io/badge/scikit_learn-0.24.1-F7931E?style=for-the-badge&logo=scikit-learn)
![](https://img.shields.io/badge/SciPy-1.6.1-8CAAE6?style=for-the-badge&logo=SciPy)

## Introduction

In statistics, `hierarchical clustering` (also called hierarchical cluster analysis or HCA) is a method of cluster analysis which seeks to build a hierarchy of clusters. Strategies for hierarchical clustering generally fall into two types:

-Agglomerative: This is a "bottom-up" approach: each observation starts in its own cluster, and pairs of clusters are merged as one moves up the hierarchy.

-Divisive: This is a "top-down" approach: all observations start in one cluster, and splits are performed recursively as one moves down the hierarchy.

In general, the merges and splits are determined in a greedy manner. The results of hierarchical clustering are usually presented in a dendrogram.

<img width="400px" src="img.png">

In the [Notebook](Notebook.ipynb), we learn how to use scipy and scikit-learn to implement Agglomerative hierarchical clustering which is more popular than the Divisive one. 

## Thanks for Reading :)
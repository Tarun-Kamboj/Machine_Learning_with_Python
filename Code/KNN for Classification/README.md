# K-Nearest Neighbors(KNN) algorithm

![](http://ForTheBadge.com/images/badges/made-with-python.svg) 

## Dependencies

![](https://img.shields.io/badge/pandas-1.2.3-150458?style=for-the-badge&logo=pandas)
![](https://img.shields.io/badge/numpy-1.19.2-013243?style=for-the-badge&logo=NumPy)
![](https://img.shields.io/badge/matplotlib-3.3.4-224099?style=for-the-badge)
![](https://img.shields.io/badge/scikit_learn-0.24.1-F7931E?style=for-the-badge&logo=scikit-learn)

## Introduction

`K-Nearest Neighbors` is an algorithm for supervised learning. Where the data is 'trained' with data points corresponding to their classification. Once a point is to be predicted, it takes into account the 'K' nearest points to it to determine it's classification.

<img width="500px" src="img.png">

In this case, we have data points of Class A and B. We want to predict what the star (test data point) is. If we consider a k value of 3 (3 nearest data points) we will obtain a prediction of Class B. Yet if we consider a k value of 6, we will obtain a prediction of Class A.

In this sense, it is important to consider the value of k. But hopefully from this diagram, you should get a sense of what the K-Nearest Neighbors algorithm is. It considers the 'K' Nearest Neighbors (points) when it predicts the classification of the test point.

In the [Notebook](Notebook.ipynb), we learn how to use scikit-learn to implement K-Nearest Neighbors algorithm. 

## Thanks for Reading :)
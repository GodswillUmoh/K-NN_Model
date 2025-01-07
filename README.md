# K-Nearest Neighbors (K-NN) Model

## Definition
> The K-Nearest Neighbors (K-NN) algorithm is a simple yet powerful machine learning algorithm used for both classification and regression tasks. It is a non-parametric and lazy learning algorithm that makes predictions based on the similarity between the data points.

## Key Characteristics
+ Non-Parametric:
_K-NN does not assume any underlying data distribution, making it flexible for various datasets._

+ Lazy Learning:
_The model does not build an explicit training model; instead, it memorizes the training data and performs computation during prediction._

+ How K-NN Works
_1. Choose the Number of Neighbors (K): Select the value of K, which represents the number of closest data points (neighbors) to consider for making predictions._
_2. Measure Distance: Calculate the distance between the data point to predict (query point) and all points in the dataset using a distance metric (e.g., Euclidean distance)._

### Euclidean Distance
> Euclidean distance is a measure of the straight-line distance between two points in a multidimensional space. It is one of the most commonly used distance metrics in machine learning and statistical analysis, particularly in algorithms like K-Nearest Neighbors (K-NN), K-Means Clustering, and Support Vector Machines (SVM).

## Pros and Cons
+ Pros
> 1. Simple and easy to implement.
> 2. Works well with smaller datasets and lower-dimensional data.
> 3. No training phase required.

+ Cons
> 1. Computationally expensive during prediction, especially with large datasets.
> 2. Sensitive to the choice of K and distance metric.
> 3. Performs poorly on high-dimensional data due to the "curse of dimensionality."

## Before and After K-NN Visuals
+ [Click to view graph 1](https://ibb.co/NZ1yg9P)
+ [K-NN Graph 2, Click to view](https://ibb.co/9hDsY37)
### How do you find the Euclidean Distance?
[See formula here, click to view](https://ibb.co/FWz194m)
_That is square root of the summation of the squares of each cordinates_

## Regular Steps for K-NN
+ 1. Choose the number k of neighbors (_Common default value is 5_)
+ 2. Take the k nearest neighbors of the two data points, according to the Euclidean Distance
+ 3. Among these k neighbors, count the number of data points in each category
+ 4. Assign the new data point to the category where you counted the most neighbors
+ Your model is Ready!

## Activity
_In the diagram below, there are two category, and a new data point is introduced. The 5 nearest neighbors are rounded, where will the new data point be assigned?_
[Click to view graph and answer the question](https://ibb.co/M1Py0GQ)

### Hints: 
_Use Step Number 4 as guide

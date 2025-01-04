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


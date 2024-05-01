# K-Nearest-Neighbors-with-Python

## 1. Introduction
The K-Nearest Neighbors (KNN) algorithm is a straightforward, non-parametric, and versatile method used in both classification and regression tasks. It operates on the principle that similar items tend to be closer to each other in feature space.

-------------------------------------------------------------------------------------------------------------
_Knn uses follwoing as a distance function_ :  

  ![knn](http://www.saedsayad.com/images/KNN_similarity.png)
 
**1)Euclidean distance** is calculated as the square root of the sum of the squared differences between a new point (x) and an existing point (xi) across all input attributes j.

EuclideanDistance(x, xi) = sqrt( sum( (xj – xij)^2 ) )

**2)Manhattan Distance:** Calculate the distance between real vectors using the sum of their absolute difference. Also called City Block Distance. 

**3)Minkowski Distance:** Generalization of Euclidean and Manhattan distance.

**Different disciplines in KNN**

**1) Instance-Based Learning:** The raw training instances are used to make predictions.
As such KNN is often referred to as instance-based learning or a case-based learning 
(where each training instance is a case from the problem domain).

**2) Lazy Learning:** No learning of the model is required and all of the work happens 
at the time a prediction is requested. As such, KNN is often referred to as a lazy learning algorithm.

**3)Non-Parametric:** KNN makes no assumptions about the functional form of the problem 
being solved. As such KNN is referred to as a non-parametric machine learning algorithm.

## 2. Theoretical Foundation
KNN is based on feature similarity, where the closeness of examples in the feature space is used to predict the classification or value of new data points. The key components of KNN include:
- **Distance Metrics**: Euclidean, Manhattan, or Hamming distances are commonly used to calculate the proximity between data points.
- **K Value**: The number of nearest neighbors to consider. A smaller K can make the algorithm sensitive to noise, while a larger K makes it more resilient but potentially less precise.
- **Decision Rule**: For classification, the output is determined by majority voting among the K nearest neighbors; for regression, it is typically the average of the values.

## 3. Algorithm Process
1. **Load Data**: Prepare the training and test datasets.
2. **Choose K and Distance Metric**: Select the number of neighbors and the metric for measuring distance.
3. **Find Neighbors**: For each test instance, locate the K nearest neighbors in the training dataset.
4. **Decision Making**: Predict the output based on majority voting or averaging.
5. **Output Prediction**: Return the prediction for the test instance.

## 4. Applications
KNN has a wide range of applications including:
- **Finance**: Credit scoring and fraud detection.
- **Healthcare**: Medical diagnosis and treatment planning based on similar patient records.
- **Retail**: Product recommendations based on customer similarity.
- **Agriculture**: Monitoring and classifying crop health.
- **Robotics**: Real-time decision-making through sensory data analysis.

## 5. Advantages
- **Ease of Implementation**: KNN is easy to implement and understand.
- **Highly Effective**: It can be very effective if the data set is large enough and well-prepped.
- **Flexibility**: Suitable for both classification and regression tasks.

## 6. Disadvantages
- **Scalability**: Computationally expensive as it involves calculating distances for each query to all training samples.
- **Curse of Dimensionality**: Performance can degrade with high-dimensional data.
- **Sensitivity to Noise**: Outliers and noise can significantly affect the predictions.

## 7. Conclusion
KNN is favored for its simplicity and effectiveness, especially in scenarios where the decision boundary is irregular. To mitigate its disadvantages, preprocessing steps such as scaling, outlier removal, and dimensionality reduction are crucial. Additionally, using advanced techniques like approximate nearest neighbors can enhance its scalability.


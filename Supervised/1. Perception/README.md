# Perceptron Model on Iris Dataset

This repository contains a Python notebook that demonstrates the implementation and evaluation of a Perceptron model using the Iris dataset. The primary focus is on binary classification to distinguish between Iris-setosa and other Iris species.

## Project Overview

The project explores the capabilities of the Perceptron, a foundational artificial neural network model, in classifying linearly separable data. Using the Iris dataset, we assess the model's performance in distinguishing Iris-setosa from Iris-versicolor and Iris-virginica based on sepal and petal measurements.

## Repository Structure

- `Perceptron.ipynb`: Jupyter notebook with the full implementation and evaluation of the Perceptron model.

## Features

The notebook covers several key aspects:
- **Data Preprocessing**: Encoding categorical data and splitting the dataset into training and testing sets.
- **Model Training**: Configuring and training the Perceptron model.
- **Evaluation**: Assessing model performance with accuracy metrics and generating classification reports.
- **Visualization**: Plotting decision boundaries and accuracy over iterations to visually assess the model's effectiveness.

## Implementation Details

The notebook `Perceptron.ipynb` follows these steps:
1. **Data Preparation**: The dataset is first preprocessed to convert categorical labels into numerical form. We then split the data into training and testing sets.
2. **Model Configuration**: A Perceptron model is initialized with parameters including the learning rate and maximum iterations.
3. **Training**: The model is trained on the processed data, where it learns to classify between the classes.
4. **Evaluation**: Post-training, the model's performance is evaluated on both training and test data using accuracy scores and detailed classification reports.

## Conclusion

The Perceptron model achieves exemplary performance, indicating its robustness in handling linear classification tasks. This project showcases the model's ability to achieve high accuracy, especially in distinguishing Iris-setosa from other species, which underscores the Perceptron's utility as a powerful yet simple machine learning tool. The visualizations provided illustrate how effectively the model separates the classes, reinforcing the importance of proper feature selection and model tuning in machine learning.


## Technologies Used

- Python: Primary programming language.
- Scikit-Learn: Machine learning library used for implementing the Perceptron model and evaluating its performance.
- Matplotlib and MLXtend: Libraries used for creating visualizations of the model's decision boundaries and performance metrics.

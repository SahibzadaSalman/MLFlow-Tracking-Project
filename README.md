# First ML Project with MLFlow Tracking

This is my first ML project where I used MLFlow to track experiments, log parameters, and metrics, and manage the lifecycle of a logistic regression model built on the Iris dataset.

## Overview

This project demonstrates:
- Training a Logistic Regression model on the Iris dataset.
- Tracking experiments and model parameters using MLFlow.
- Logging model metrics like accuracy and confusion matrix.
- Saving the trained model with MLFlow for future use.

## Features

1. **MLFlow Experiment Tracking**:
   - Logs parameters, metrics, and model artifacts.
   - Manages experiment versions using MLFlow Tracking and Model Registry.

2. **Logistic Regression Model**:
   - Trained and evaluated on the Iris dataset.
   - Metrics include accuracy, confusion matrix, precision, recall, and F1-score.

3. **Model Logging**:
   - The trained model is saved and versioned using MLFlow's model logging feature.

## Technologies Used

- **Python**: Programming language for the project.
- **MLFlow**: For experiment tracking and model management.
- **Scikit-learn**: For dataset handling, model training, and evaluation.

## Dataset

- **Iris Dataset**: A built-in dataset from Scikit-learn, which contains 150 samples of iris flowers with 4 features (sepal length, sepal width, petal length, petal width) and 3 classes (setosa, versicolor, virginica).

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/MLFlow-Tracking-Project.git

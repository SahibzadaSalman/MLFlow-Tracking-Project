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

## Project Workflow

1. **Data Preparation**:
   - Load the Iris dataset and split it into training and testing sets.

2. **Model Training**:
   - Train a Logistic Regression model using Scikit-learn with specified hyperparameters.

3. **Model Evaluation**:
   - Evaluate the model using metrics like accuracy and confusion matrix.

4. **MLFlow Integration**:
   - Log parameters, metrics, and artifacts using MLFlow.
   - Save the trained model to the MLFlow Model Registry for future use.

## How to Run the Project

### Prerequisites

1. Install Python (3.7 or higher).
2. Install the required libraries:
   ```bash
   pip install mlflow scikit-learn pandas numpy

## Steps to Run

1. **Clone this Repository**:
   - git clone https://github.com/SahibzadaSalman/MLFlow-Tracking-Project.git

2. **Navigate to Project Directory**: 
   - cd MLFlow-Tracking-Project

3. **Start the MLFlow Tracking Server**:
   - mlfow ui
   - This command sets up a local MLFlow tracking server at http://127.0.0.1:5000.

4. **Open the Jupyter Notebook**:
   - Run the file ML_Project.ipynb in Jupyter Notebook or any Python IDE.
   - Execute each cell to train the model, log results, and track experiments in MLFlow.

5. **Access the MLFlow UI**:
   - Open your browser and go to http://127.0.0.1:5000 to view the logged experiments and models.

## Results
   - Accuracy: Logged for every experiment run.
   - Confusion Matrix: Provides insights into the model's performance.
   - Model Signature: Ensures correct input-output mapping for the logged model.

## Project Highlights
1. **Experiment Tracking**:
   - Multiple runs are tracked to compare results across different model parameters and metrics.

2. **Model Versioning**:
   - Models are saved with a unique version identifier for easy reproducibility.

3. **Model Registry Integration**:
   - Models are registered for future deployment.

## Future Improvements
   - Add advanced models like Random Forest or SVM for comparison.
   - Use larger, more complex datasets for real-world scenarios.
   - Automate the deployment pipeline using MLFlow's Model Registry and serving tools.

## Author
**Sahibzada Salman**
Beginner in MLFlow and Machine Learning experiment tracking.
Feel free to reach out for collaboration or questions!
# Diabetes Prediction using Machine Learning

## Overview
This project implements a machine learning model to predict whether a patient is likely to have diabetes based on medical data. The dataset used is the **PIMA Indians Diabetes Dataset**.

## Dataset
The dataset consists of several medical predictor variables, such as:
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin Levels
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age

The target variable is **Outcome**, which indicates whether a person has diabetes (1) or not (0).

## Model
The model used in this project is **Logistic Regression**, a simple yet effective classification algorithm.

### Steps Involved:
1. **Data Preprocessing**: Standardizing the feature values.
2. **Splitting the Dataset**: 80% training and 20% testing.
3. **Model Training**: Logistic Regression model was used for training.
4. **Model Evaluation**: The model's accuracy, confusion matrix, and classification report were used to evaluate performance.

## Results
- **Accuracy**: Achieved an accuracy score of the model on the test data.
- **Confusion Matrix**: Shows the true positives, false positives, true negatives, and false negatives.
- **Classification Report**: Provides precision, recall, F1-score, and support for the model's predictions.

## How to Run
1. Clone the repository.
2. Install necessary dependencies:
   ```bash
   pip install -r requirements.txt

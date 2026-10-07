# Diabetes Risk Prediction using Machine Learning

An end-to-end machine learning project for predicting diabetes risk using patient health-related features. The project covers data preprocessing, exploratory data analysis, feature scaling, model training, and model evaluation using multiple classification algorithms.

## Project Overview

The objective of this project is to build machine learning models that can predict whether a patient is likely to have diabetes based on health-related attributes.

The project uses the Pima Indians Diabetes dataset containing 768 patient records and 8 input features.

## Dataset

The dataset contains the following features:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

### Target Variable

- Outcome
  - 0: No diabetes
  - 1: Diabetes

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- XGBoost
- Jupyter Notebook

## Machine Learning Workflow

The project follows the following workflow:

1. Data Loading
2. Data Inspection
3. Exploratory Data Analysis
4. Statistical Analysis
5. Missing and Invalid Value Analysis
6. Outlier Detection
7. Data Preprocessing
8. Feature Scaling
9. Train-Test Split
10. Model Training
11. Model Prediction
12. Model Evaluation
13. Model Comparison

## Data Preprocessing

The dataset was analyzed for invalid zero values and outliers.

The project includes preprocessing and outlier handling for features such as:

- Insulin
- DiabetesPedigreeFunction
- SkinThickness
- BloodPressure

Feature scaling was performed using `StandardScaler`.

## Machine Learning Models

The following classification algorithms were implemented and evaluated:

### Logistic Regression

Logistic Regression was used as a baseline classification model.

Test Accuracy:

```text
77.92%

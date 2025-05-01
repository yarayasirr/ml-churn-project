# Customer Churn Prediction with Machine Learning

## Project Overview

This project aims to predict customer churn for a telecom company using machine learning techniques. The goal is to understand the factors influencing churn and build predictive models that can help the company retain valuable customers.

This project is a basic introduction to machine learning, with the aim of creating a **predictive model** using various techniques.


## Technologies Used

- **Python**: The primary programming language used for data manipulation and machine learning.
- **pandas**: Data manipulation and analysis library.
- **scikit-learn**: Library for machine learning algorithms, data preprocessing, and model evaluation.
- **numpy**: An efficient implementation of data manipulation.
- **matplotlib** & **seaborn**: Libraries for data visualization.
- **Jupyter Notebook**: Interactive notebook used for running code and documenting the analysis.

## Data Overview

The dataset used in this project is a **telecom customer dataset** that contains information about customers from Kaggle.com.

## Data Preprocessing

The data preprocessing steps include:

1. **Data Cleaning**:
   - Removed missing or duplicate values.
   - Addressed outliers where applicable.

2. **Feature Engineering**:
   - Applied **label encoding** to categorical variables.

3. **Feature Scaling**:
   - Standardized numerical features (e.g., `Tenure`) to ensure all features are on the same scale using **StandardScaler**.

4. **Train-Test Split**:
   - The dataset was split into training (80%) and testing (20%) sets using `train_test_split` from scikit-learn.

## Modeling Process

Various machine learning algorithms were tested, including:

1. **Logistic Regression**:
   - A simple linear model used as a baseline for binary classification.

2. **Random Forest Classifier**:
   - An ensemble learning method that uses multiple decision trees to improve classification accuracy.


## Evaluation Metrics

The models were evaluated using the following metrics:

- **Accuracy**: The proportion of correctly classified instances.
- **Precision**: The ability of the model to correctly identify positive instances.
- **Recall**: The ability of the model to correctly identify all relevant instances.
- **F1-Score**: The harmonic mean of precision and recall.

## Results

After training and evaluating the models:

Random Forest gave the best balance between **precision**, **recall**, and **F1-score**, making it the preferred model.



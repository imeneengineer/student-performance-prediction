# Student Performance Prediction

A machine learning project focused on predicting students' final grades using Random Forest Regression.

## Overview

The goal of this project was to explore the factors influencing students' academic performance and build a regression model to predict their final grades (G3).

I used the Student Performance dataset from the UCI Machine Learning Repository.

## Dataset

- Dataset: Student Performance (Mathematics)
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/320/student+performance)
- Number of students: 395
- Number of features: 32 input features and 1 target variable

The target variable is G3, representing students' final grades, ranging from 0 to 20.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

### 1. Exploratory Data Analysis

- Inspected the dataset structure and checked for missing values and duplicates.
- Analyzed the distribution of the final grades.
- Explored relationships between features and the target variable.
- Investigated correlations between G1, G2, and G3.

### 2. Data Preprocessing

- Separated numerical and categorical features.
- Prepared the data for machine learning.
- Split the dataset into training and testing sets.
- Compared models using different feature sets.

### 3. Model Building

I selected Random Forest Regression because it can capture nonlinear relationships between features and the target variable.

I trained the model using the students' previous grades (G1 and G2) and other academic and personal features.

### 4. Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The model achieved the following results:

| Metric | Score |
|---|---:|
| MAE | 1.188 |
| RMSE | 2.007 |
| R² | 0.800 |

### 5. Feature Importance

I used permutation importance to investigate how much each feature contributed to the model's predictions.

G2 was the most influential feature, followed by absences.

I also compared model performance using different feature sets to understand the impact of previous grades on the predictions.

## What I Learned

- How to perform exploratory data analysis on a real-world dataset.
- How to preprocess data for regression tasks.
- How to train and evaluate a Random Forest Regression model.
- How to interpret MAE, RMSE, and R².
- How to use feature importance and permutation importance.
- How to compare models using different feature sets.
- Why previous academic grades are highly predictive of final grades.

## Author

Imene

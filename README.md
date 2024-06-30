# Student Performance Prediction: Data Analysis and Machine Learning

## Introduction

This project aims to analyze and predict student outcomes based on a dataset encompassing various educational factors. By leveraging data preprocessing techniques, exploratory data analysis (EDA), and machine learning models, we seek to understand the factors influencing student success, dropout rates, and enrollment patterns. Through visualization and predictive modeling, this analysis provides insights into educational trends and identifies key predictors that contribute to student performance. The project utilizes Python libraries such as NumPy, Pandas, Matplotlib, Seaborn, and scikit-learn to conduct thorough analysis and build predictive models for educational data.

## Data Preprocessing & Visualization

### Data Overview

- Checked dataset information and handled missing values.
- Encoded categorical variables for analysis.

### Visualization

- Explored data distributions and relationships using:
  - Histograms (`sns.distplot`)
  - Pie chart (`plt.pie`)
  - Count plots (`sns.countplot`)
  - Box plots (`sns.boxplot`)

## Feature Selection and Engineering

- Identified top features correlated with the target variable.
- Dropped irrelevant columns for model building.

## Model Building

### Splitting Data

- Divided data into training and testing sets (`train_test_split`).

### Model Implementation

- Utilized various classifiers:
  - Logistic Regression
  - K-Nearest Neighbors
  - Decision Trees
  - Random Forest
  - Naive Bayes

### Model Evaluation

- Evaluated models using metrics:
  - Accuracy (`accuracy_score`)
  - Precision (`precision_score`)
  - Recall (`recall_score`)

## Model Optimization

### Pipeline Implementation

- Implemented preprocessing pipeline (`Pipeline`, `ColumnTransformer`).

### Ensemble Methods

- Explored ensemble methods for improved model accuracy (`VotingClassifier`).

## Model Evaluation

### Learning Curve

- Visualized learning curves to assess model performance (`learning_curve`).

### Confusion Matrix

- Displayed confusion matrix for the best performing model (`confusion_matrix`).


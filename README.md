# house-price-prediction-ml
A  machine learning pipeline for house price prediction using linear regression models, featuring data preprocessing, feature engineering (Pearson correlation, mutual information, PCA), and comparative analysis of Linear, Lasso, and Ridge regression with evaluation metrics.

## Project Overview

This project implements a full machine learning workflow for house price prediction, including data preprocessing, feature selection, feature extraction, and model evaluation using multiple regression approaches.

## Features

### Part 1: Data Preprocessing
- Removed duplicate and missing data entries to ensure data quality and completeness
- Converted all non-numerical features to numerical representations using appropriate encoding techniques
- Detected and removed outliers that significantly impact model performance
- Applied standardization and normalization to bring all features to consistent scales, preventing model bias

### Part 2: Feature Selection
- Implemented feature selection techniques to identify meaningful relationships between features
- Used Pearson correlation analysis to measure linear relationships
- Applied mutual information (MI) to capture non-linear feature dependencies
- Selected only features with significant correlations to the target variable

### Part 3: Feature Extraction
- Applied Principal Component Analysis (PCA) for dimensionality reduction
- Extracted new features that preserve information from original features while reducing complexity
- Highlighted important patterns in the data to improve model performance

### Part 4: Linear Regression Models
- Split data into training and testing sets for proper model evaluation
- Implemented and compared three regression approaches:
  - **Simple Linear Regression**: Basic linear modeling
  - **Lasso Regression**: L1 regularization for feature selection
  - **Ridge Regression**: L2 regularization to prevent overfitting
- Analyzed differences, use cases, and performance of each method

### Part 5: Model Evaluation
- Evaluated models using multiple metrics including MSE, RMSE, MAE, and R²
- Compared performance across different regression techniques
- Analyzed and visualized results with comprehensive plots
- Provided detailed analysis of regularization effects on model performance

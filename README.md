# California Housing Regression

## Overview

This project aims to predict housing prices in California using various regression algorithms. We will employ simple linear regression, multiple linear regression, decision tree regression, and support vector regression (SVR) to model the relationship between the features and the target variable (median house value).

## Dataset

The dataset used in this project is the California Housing dataset, which contains information about housing prices and various features for different districts in California. The features include median income, housing median age, average rooms, average bedrooms, population, households, latitude, and longitude.

## Regression Algorithms

1. **Simple Linear Regression**: This model assumes a linear relationship between the feature and target variable. It predicts the target variable using a single feature.
   
2. **Multiple Linear Regression**: Similar to simple linear regression, but it considers multiple features to predict the target variable.

3. **Decision Tree Regression**: This algorithm partitions the feature space into regions and fits a simple model (e.g., mean) in each region. It can capture non-linear relationships between features and the target variable.

4. **Support Vector Regression (SVR)**: SVR uses support vector machines (SVM) to perform regression. It finds the hyperplane that maximizes the margin while still fitting as many instances as possible within a margin of tolerance. 

## Evaluation Metrics

The performance of each regression model will be evaluated using the following metrics:

- **R² (R-squared)**: This metric quantifies the proportion of the variance in the dependent variable that is predictable from the independent variables.
  
- **MAE (Mean Absolute Error)**: This metric calculates the average absolute difference between the predicted and actual values. It provides an easy-to-understand representation of the model's accuracy.

- **MSAE (Mean Squared Absolute Error)**: This metric calculates the average of the squared absolute differences between the predicted and actual values. It penalizes larger errors more heavily than MAE.

## Implementation

The project involves the following steps:

1. **Data Loading**: Load the California Housing dataset.

2. **Data Preprocessing**: Preprocess the data if necessary, such as handling missing values, scaling features, and splitting into training and testing sets.

3. **Model Training**: Train each regression model using the training data.

4. **Model Evaluation**: Evaluate the performance of each model using the specified evaluation metrics.

5. **Comparison**: Compare the performance of different regression algorithms and select the best-performing model.

## Dependencies

- Python 3.x
- NumPy
- Pandas
- scikit-learn

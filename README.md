# Hurricane Impact Model – Sample Code

This repository contains sample code for building a **Hurricane Impact Model** using machine learning techniques. It demonstrates the full workflow, from data collection and preprocessing to model training, evaluation, and prediction.

## Overview

The notebook includes the following key steps:

1. **Data Collection**
   - Import hurricane-related datasets.
   - Explore and reshape data for modeling.
2. **Data Cleaning**
   - Handle missing values (`NaN`) and outliers.
3. **Feature Engineering**
   - Normalize and encode features using `StandardScaler` and `OneHotEncoder`.
4. **Model Training**
   - Train several models:
     - Linear Regression
     - Ridge & Lasso Regression
     - Support Vector Machine (SVM)
     - Decision Tree
     - Random Forest Regressor
     - Multi-layer Perceptron (MLP) Regressor
5. **Model Evaluation**
   - Evaluate model performance using:
     - R² score
     - Mean Squared Error
     - Explained Variance Score
   - Use cross-validation for robust performance estimates.
6. **Hyperparameter Tuning**
   - Grid Search and Randomized Search for optimal model parameters.

## Usage

This sample notebook is intended for use in:

This sample notebook demonstrates how to build and evaluate a hurricane impact model that can be easily adapted in the future for:

- Enterprise risk modeling: quantifying property-level loss exposure across multiple perils, including hurricanes.

- Catastrophe risk analysis: generating hurricane-specific loss estimates and aggregate exceedance probability curves.

- Insurance claims forecasting: predicting claim frequency and severity following landfall, to support underwriting, pricing, and reserve setting.

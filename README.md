# Crop-Price-Prediction

This repository contains the implementation of a data-driven project titled CROP PRICE PREDICTION, focused on analyzing and predicting crop prices in Rajasthan, India, using advanced machine learning models. The project leverages multiple datasets, including crop production, water usage, soil analysis, and market prices, to create an integrated model for price prediction. The repository provides a comprehensive approach to Exploratory Data Analysis (EDA), feature engineering, and hyperparameter tuning for multiple machine learning algorithms.

Link of Dataset used: https://www.kaggle.com/datasets/suraj520/agricultural-data-for-rajasthan-india-2018-2019/data 

Key Features- Dataset Integration Merges and preprocesses multiple datasets:
  1. Crop production data
  2. Water usage data
  3. Soil analysis data
  4. Crop price data

Data Preprocessing
  1. Handles missing values and duplicates
  2. Encodes categorical variables
  3. Standardizes numerical features using MinMaxScaler
  4. Extracts temporal features from date columns
  5. Exploratory Data Analysis (EDA)- Generates comprehensive profiling reports using ydata-profiling
Visualizes data distributions, correlations, and feature importance

Feature Engineering and Selection
  1. Uses Random Forest Regressor to identify and select the most important features for the model

Machine Learning Models-  
Implements and fine-tunes the following regression models using GridSearchCV:
  1. XGBoost Regressor
  2. Light Gradient Boosting Machine (LightGBM) Regressor
  3. Gradient Boosting Regressor

Performance Evaluation
  1. Calculates R² score and Mean Squared Error (MSE) for model comparison
  2. Visualizes model performance using bar charts


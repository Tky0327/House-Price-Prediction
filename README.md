# USA House Price Prediction

This project aims to predict house prices in the USA using machine learning models. It includes data preprocessing, exploratory data analysis (EDA), and the implementation of various regression models. Additionally, a Streamlit app is developed for user interaction, and a Power BI dashboard is created for data visualization.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
  - [Random Forest Model](#random-forest-model)
  - [Gradient Boosting Model](#gradient-boosting-model)
  - [Decision Tree Model](#decision-tree-model)
  - [Ridge Regression Model](#ridge-regression-model)
  - [Hybrid Regression Model](#hybrid-regression-model)
- [Evaluation](#evaluation)
- [Results](#results)
- [Power BI Dashboard](#power-bi-dashboard)
- [Streamlit App](#streamlit-app)


## Overview

This project is focused on building machine learning models to predict house prices in the USA based on various features. It involves data preprocessing, EDA, and modeling with Random Forest, Gradient Boosting, Decision Tree, Ridge Regression, and a Hybrid Regression model. The project also includes a user-friendly Streamlit app and a Power BI dashboard for visualizing the data insights.

## Dataset

The dataset used in this project is sourced from [https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset?resource=download]. It contains various features such as the number of bedrooms, bathrooms, area in square feet, and more, along with the target variable, which is the house price.

## Data Preprocessing

The data preprocessing steps include:
- Handling missing values
- Encoding categorical variables
- Normalizing or standardizing the data
- Splitting the data into training and testing sets

## Exploratory Data Analysis

EDA is performed to understand the data distribution, correlations, and patterns. Various visualizations and statistical measures are used to gain insights into the dataset.

## Modeling

### Random Forest Model

A Random Forest model is used to capture complex, nonlinear relationships in the data through an ensemble of decision trees.

### Gradient Boosting Model

The Gradient Boosting model builds an ensemble of trees in a sequential manner, optimizing the model to minimize errors iteratively.

### Decision Tree Model

A simple Decision Tree model is applied to the dataset to understand the basic tree structure's performance in predicting house prices.

### Ridge Regression Model

Ridge Regression, a regularized linear regression model, is used to handle multicollinearity in the data and improve prediction accuracy.

### Hybrid Regression Model

The Hybrid Regression model combines the predictions of multiple models (e.g., Random Forest, Ridge Regression) to leverage their strengths and improve overall performance.

## Evaluation

The models are evaluated using metrics such as:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²) Score

## Results

The results section contains the performance metrics for each model and a discussion of their comparative effectiveness.

## Power BI Dashboard

An interactive dashboard is created to visualize key insights such as average house price, price per square foot, etc.

## Streamlit App

A Streamlit app is developed to provide an interactive user interface for the house price prediction model. Users can input various features, and the app predicts the house price in real-time.



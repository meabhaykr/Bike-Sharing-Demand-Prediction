# Bike Sharing Demand Prediction

![ezgif.com-gif-maker.gif](https://github.com/meabhaykr/Bike-Sharing-Demand-Prediction/blob/main/Image/ezgif.com-gif-maker.gif)

## Project Summary

The objective of this project is to improve public mobility and convenience through bike-sharing programs in urban areas, with a focus on predicting the demand for bike-sharing services in Seoul. It involves data preparation, model building, and evaluation to address the practical challenge of ensuring a consistent supply of bikes for rental in metropolitan areas.

## Problem Statement

In metropolitan areas, bike-sharing programs enhance public mobility and convenience, but maintaining a consistent supply of rental bikes is a critical challenge. This project leverages historical data, including factors like temperature and time, to forecast the demand for Seoul's bike-sharing program. The goal is to optimize bike supply and meet the dynamic needs of the city's residents, reducing waiting times for the public.

## Business Objective

Predicting the optimal number of bikes needed at any specific moment and day is crucial for bike rental businesses. Striking the right balance is essential to maximize resource utilization and ensure a seamless experience for customers. Accurate demand forecasts are vital for informed decision-making and the overall success of bike-sharing enterprises.

## Data Overview

The dataset consists of approximately 8,760 records and 14 attributes. These attributes include information about bike rental counts, time, weather conditions, and more.

## EDA & Visualization

- Explored and visualized the dataset, creating new features and analyzing key columns, such as 'hour,' 'temperature,' 'humidity,' and more.
- Conducted regression plots, correlation coefficient analysis, and used heatmaps to visualize relationships.
- Explained the importance of VIF (Variance Inflation Factor) analysis and encoding techniques for feature engineering.
- Applied normalization to the target variable.

## Data Cleaning

- Identified and addressed duplicate values, missing values, skewness, and outliers in the dataset.

## Feature Engineering & Data Pre-processing

- Carried out regression plot analysis, calculated correlation coefficients, and applied VIF analysis for feature selection.
- Explained encoding techniques for categorical variables and the normalization of the target variable.

## ML Model Implementation

- Split the data into training and testing sets.
- Scaled the data for modeling.
- Implemented various machine learning models, including Linear Regression, Lasso, Ridge, Elastic Net, K-Nearest Neighbors, Support Vector Machine, Decision Tree, and Random Forest.
- Conducted hyperparameter tuning for the Random Forest model.
- Evaluated model performance using multiple metrics, with a focus on R2 score and RMSE score.

## Model Implementation

- Detailed the implementation of various machine learning models and presented their results.

## MODEL RESULT
- The R-squared measure is useful for assessing the relationship between dependent and independent variables, but it doesn't address overfitting. In complex regression models, Adjusted R-squared is valuable as it considers variable relationships and penalizes unnecessary ones, reducing overfitting risks. R-squared is still reliable for understanding predictability in rented_bike_count.

![Results.png](https://github.com/meabhaykr/Bike-Sharing-Demand-Prediction/blob/main/Image/Results.png)
![Plotting graph.png](https://github.com/meabhaykr/Bike-Sharing-Demand-Prediction/blob/main/Image/Plotting%20graph.png)

## Conclusion

This project aims to improve the supply of rental bikes for bike-sharing programs in Seoul by leveraging historical data and machine learning models. By accurately predicting demand, bike-sharing businesses can operate more efficiently and provide a better experience for their customers, ultimately benefiting both service providers and the public.

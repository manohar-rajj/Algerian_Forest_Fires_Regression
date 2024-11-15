# Algerian Forest Fires - Multiple Regression ML Project

Overview:
The Algerian Forest Fires project applies multiple linear regression techniques to predict forest fire occurrence in Algeria based on various meteorological and environmental factors. The dataset contains information about forest fires that occurred between 2000 and 2012 in the forests of Algeria, with variables including temperature, humidity, wind speed, and more. The goal of the project is to understand the relationships between these factors and forest fire occurrences using regression algorithms like Lasso, Ridge, and Elastic Net.

Objective:
The main objectives of this project are:
Data Cleaning: Preprocessing the raw dataset to handle missing values, outliers, and irrelevant features.
Exploratory Data Analysis (EDA): Analyzing the dataset to uncover patterns, trends, and insights.
Modeling: Training multiple regression models (Linear Regression, Lasso, Ridge, Elastic Net) to predict the area burned by forest fires.
Model Evaluation: Using cross-validation techniques to evaluate the performance of the models and select the best-performing one.
Insights: Drawing conclusions about which features have the most influence on the occurrence and size of forest fires in Algeria.
Key Concepts Used
Multiple Linear Regression: Used as the foundation of the model to predict continuous values (ISI).
Lasso Regression: A linear regression model that adds L1 regularization to improve model sparsity and reduce overfitting.
Ridge Regression: A linear regression model with L2 regularization to prevent overfitting by shrinking coefficients.
Elastic Net: A hybrid model combining L1 and L2 regularization to balance the strengths of Lasso and Ridge. 

This projects includes the following features:
Date : (DD/MM/YYYY) Day, month ('june' to 'september'), year (2012)
Weather data observations: 
Temp : temperature noon (temperature max)  in Celsius degrees: 22 to 42
RH : Relative Humidity in %: 21 to 90 
Ws :Wind speed in km/h: 6 to 29 
Rain: total day in mm: 0 to 16.8
FWI Components:  
Fine Fuel Moisture Code (FFMC) index from the FWI system: 28.6 to 92.5 
Duff Moisture Code (DMC) index from the FWI system: 1.1 to 65.9 
Drought Code (DC) index from the FWI system:  7 to 220.4
Initial Spread Index (ISI) index from the FWI system: 0 to 18.5 
Buildup Index (BUI) index from the FWI system: 1.1 to 68
Fire Weather Index (FWI) Index: 0 to 31.1
Classes: two classes, namely 'fire','not fire'

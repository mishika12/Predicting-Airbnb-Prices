###  Predicting Airbnb Prices Using Regression Optimization

### <ins> Introduction
Accurately predicting Airbnb prices is crucial for hosts and guests alike. This project focuses on using regression optimization techniques to build predictive models for Airbnb listing prices based on various features.

### <ins> Problem Statement
The project involves three models for predicting Airbnb prices using data from 1700 listings in Hollywood, CA:

Model 1: Formulate and solve a least absolute deviations (LAD) regression problem to predict prices and evaluate the prediction error on a test set.
Model 2: Enhance model interpretability by restricting the model to only the three most important variables. Include a constraint to select at most three variables with non-zero coefficients and report the prediction error.
Model 3: Build a model using exactly three variables, one of which is the number of beds. Identify the two additional variables selected, compare with Model 2, and report the prediction error.

### <ins> Methodology
Data Preparation: Use AirbnbTrain.csv for training and AirbnbTest.csv for evaluating model performance. The goal is to minimize the absolute deviation between predicted and actual prices.
Model Formulation and Solution 

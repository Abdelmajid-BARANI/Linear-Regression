# Linear-Regression
Overview
This script performs a simple linear regression analysis on a dataset to predict scores based on hours studied. It imports necessary libraries, fetches the data, plots the relationship between hours studied and scores, trains a linear regression model, and evaluates its performance.

Steps
Import Libraries: Uses pandas, numpy, and matplotlib for data handling and visualization.
Fetch Data: Retrieves data from a URL and displays the first 10 rows.
Plot Data: Creates a scatter plot of hours vs. scores.
Prepare Data: Splits the data into training and testing sets.
Train Model: Trains a linear regression model on the training data.
Plot Regression Line: Visualizes the regression line along with the test data.
Predict and Compare: Makes predictions on test data and compares actual vs. predicted values.
Custom Prediction: Predicts the score for a user-specified number of hours.
Evaluate Model: Computes the Mean Absolute Error (MAE) to assess model performance.
Usage
Data URL: Data is fetched from http://bit.ly/w-data.
Custom Prediction: Modify the Hours variable to predict scores for different hours studied.
Dependencies
pandas
numpy
matplotlib
scikit-learn

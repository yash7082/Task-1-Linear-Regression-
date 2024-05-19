# Task-1-Linear-Regression-
Implementing a linear regression model to predict house prices based on square footage, number of bedrooms, and number of bathrooms involves several steps. Below is a detailed implementation using Python and the popular library scikit-learn.

Step-by-Step Implementation:
Import Libraries
Load and Prepare Data
Feature Engineering
Train-Test Split
Model Training
Model Evaluation
Prediction

Explanation of Key Steps:
Data Loading: The dataset is loaded into a pandas DataFrame.
Feature Engineering: The relevant features (square footage, bedrooms, bathrooms) are selected along with the target variable (price).
Train-Test Split: The data is split into training and testing sets to evaluate the model's performance on unseen data.
Model Training: A linear regression model is initialized and trained on the training data.
Model Evaluation: The model's performance is evaluated using mean squared error (MSE) and R-squared metrics. A scatter plot is used to visualize the actual vs. predicted prices.
Prediction: The trained model is used to make predictions on new data.

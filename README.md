BANK MARKETING SUBSCRIPTION PREDICTION

Overview

  -This project analyzes a bank marketing dataset and builds machine learning models to predict whether a client will subscribe to a term deposit.
  -The goal is to support marketing decisions by identifying potential subscribers.

What I did

  -Performed exploratory data analysis (EDA)
  -Detected class imbalance in the target variable
  -Applied one-hot encoding to categorical features
  -Split the data into training and test (80/20% ratio)
  -Built Logistic Regression and Random Forest models
  -Improved recall using balanced class weight
  -Compared models based on business objectives

Results

  -Baseline Logistic Regression had high accuracy but low recall for subscribers
  -Handling class imbalance improved recall significantly
  -Model selection depends on business objective, precision vs recall trade-off

Tools used

  Python, Pandas, NumPy, Scikit-learn, Matplotlib.

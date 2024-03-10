Company Bankruptcy Detector
Overview

The Company Bankruptcy Detector is a Python program developed for predicting the likelihood of a company going bankrupt based on various financial and non-financial factors. The program utilizes logistic regression, a popular machine learning algorithm, to build a bankruptcy prediction model. By analyzing historical data and evaluating key features, the model can provide valuable insights to financial institutions, investors, and policymakers, enabling them to make informed decisions and mitigate financial risks.
Features

    Logistic Regression Model: Utilizes logistic regression for bankruptcy prediction, offering interpretability, performance, and frequent use in credit scoring models.
    Data Preprocessing: Handles data loading, preprocessing, and feature selection to prepare the dataset for model training.
    Model Training and Evaluation: Splits the dataset into training and testing sets, trains the logistic regression model, and evaluates its performance using various evaluation metrics such as accuracy, precision, recall, and F1 score.
    Prediction: Provides functionality to make bankruptcy predictions for new companies based on their feature inputs.

Usage

    Data Preparation: Prepare a dataset containing relevant features and a target variable indicating bankruptcy status (0 = not bankrupt, 1 = bankrupt).
    Model Training: Run the program to train the logistic regression model using the prepared dataset.
    Model Evaluation: Evaluate the trained model's performance using the provided evaluation metrics on a separate testing dataset.
    Prediction: Use the trained model to make bankruptcy predictions for new companies by providing their feature inputs.

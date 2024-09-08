# Supervised-Learning-Project

Project 1: Medical Domain - Predicting Patient Conditions
Project Objective

The objective of this project is to leverage AI/ML techniques to predict patient conditions based on biomechanics data using supervised learning algorithms.
Steps and Tasks

    Data Understanding:
        Read and explore 3 CSV files.
        Analyze the structure and data types.
        Compare and clean variations in the 'Class' feature.
    Data Preparation:
        Combine the datasets, check for missing values, and generate a unified DataFrame.
        Perform exploratory data analysis (EDA) and check feature correlations.
    Model Building:
        Build a KNN classification model and evaluate performance using various metrics.
    Performance Improvement:
        Experiment with different parameters to improve model accuracy.

Dataset Description

The dataset consists of biomechanics features derived from patients' conditions, with 6 key attributes. The objective is to predict the condition of the patient based on test results.
Model Performance

    Base Model: K-Nearest Neighbors (KNN) classifier.
    Performance Metrics: Accuracy, Precision, Recall, and F1-score are evaluated.

Project 2: Banking Domain - Targeted Marketing Prediction
Project Objective

This project focuses on building a machine learning model to predict potential customers who will convert during a marketing campaign, using historical data from a bank.
Steps and Tasks

    Data Understanding:
        Read and merge the datasets.
        Change data types for specific features.
        Handle missing and unexpected values.
    Data Exploration:
        Visualize the distribution of the target variable (LoanOnCard).
        Balance the dataset using appropriate techniques.
    Model Building:
        Train a Logistic Regression model.
        Evaluate using classification metrics.
    Performance Improvement:
        Train additional models (SVM, KNN) and tune hyperparameters for optimization.

Dataset Description

The data contains customer attributes such as age, highest spend, mortgage, internet banking usage, and loan on the credit card. The objective is to predict the likelihood of loan conversion for focused marketing.
Model Performance

    Base Model: Logistic Regression.
    Additional Models: Support Vector Machine (SVM), K-Nearest Neighbors (KNN).
    Performance Metrics: Accuracy, Precision, Recall, and F1-score are evaluated for both base and final models.

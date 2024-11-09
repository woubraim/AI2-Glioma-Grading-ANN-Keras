#Project 2: Predictive Analysis and Feature Selection for Cancer Data
Overview

This project expands on glioma grading, focusing on improving predictive accuracy by analyzing and selecting the most informative features from both clinical and genetic data. The goal is to identify a minimal yet highly predictive subset of features, potentially reducing data collection costs while maintaining robust glioma grading accuracy.

Dataset

    Glioma Grading Clinical and Mutation Data: The dataset, similar to AI1, includes mutation data for 20 genes and 3 clinical features such as Gender, Age_at_diagnosis, and Race.

Workflow

    1.Data Exploration:
        Conduct exploratory data analysis (EDA) to gain insights into feature distributions and relationships.

    2.Data Preprocessing:
        Handle missing values, encode categorical data, and scale numeric features.

    3.Model Training and Evaluation:
        Train multiple classifiers including logistic regression, decision tree, random forest, and SVM.
        Apply cross-validation to ensure robustness against overfitting.

    4.Hyperparameter Tuning:
        Use GridSearchCV to fine-tune model hyperparameters for maximum prediction accuracy.

    5.Feature Importance and Analysis:
        Leverage decision tree and random forest models to identify and visualize the most impactful features.

    6.Model Selection:
        Select the best-performing model and generate predictions on the test data.

Requirements

    Packages: pandas, numpy, scikit-learn, matplotlib, seaborn

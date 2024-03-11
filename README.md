# Diabetes Detection
## Deploying many basic machine learning model to detect diabetes

The model we use are:

- DesicionTreeClassifier.
- Gaussian Naive Bayes.
- K Nearest Neighbors.
- Polynomial Regression.
- Random Forest Classifier.
- Logistic Regression.

## Features

- Data preprocessing: cleaning data, analyze data, and visualize data.
- Modeling with scaled dataset using with or without GridSearch.
- Modeling with unscaled dataset using with or without GridSearch.
- Evaluating and comparing between models

## Dataset

The dataset we used is 
https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset
> A csv of the dataset available on Kaggle for the year 2015 was used. This original dataset contains responses from 441,455 individuals and has 330 features. These features are either questions directly asked of participants, or calculated variables based on individual participant responses.

## Tech

Diabetes Detection uses a number of Python modules and packages to work properly:

- [Scikit-learn] - a Python module for machine learning
- [Pandas] - a Python package that provides fast, flexible, and expressive data structures
- [NumPy] - a fundamental package for scientific computing in Python..
- [Matplotlib] - a comprehensive library for creating static, animated, and interactive visualizations in Python

## Result

|                        | train_test_split |                | KFold(5 folds) |     |
| ---------------------- | ---------------- | -------------- | ---------------- | -------------- |
| **Model**                  | **Accuracy**         | **F1 Score**       | **Accuracy** | **F1 Score** |
| Gaussian Naive Bayes   | 0.7132           | 0.7329         | 0.7112 | 0.7038 |
| DecisionTreeClassifier | 0.7369           | 0.7500         | 0.7581 | 0.7469 |
| Polynomial Regression  | **0.7564**           | 0.7564         | **0.7601** | 0.7549 |
| Logistic Regression    | 0.7449           | 0.7546         | 0.7415 | 0.7514 |
| K-nearest Neighbor     | 0.736            | 0.75           | 0.733 | 0.747 |
| RandomForestClassifier | 0.7505           | **0.7657**         | 0.7441 | **0.7590** |




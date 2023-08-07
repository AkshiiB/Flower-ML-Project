# Flower-ML-Project
Flower Classification with Machine Learning Algorithms

This repository contains code for a simple machine learning project that classifies flowers into three species: 
Setosa, Versicolor, and Virginica, based on their measurements of sepal length, sepal width, petal length, and petal width.

# Contents:
flowers.ipynb: This Jupyter Notebook contains the code for data exploration, preprocessing, and model building using various machine learning algorithms.
Dataset:

The dataset used in this project is the famous Iris dataset, which is available in the Scikit-learn library. 
It consists of 150 samples of iris flowers, with 50 samples for each species.

# Machine Learning Algorithms Used:
Logistic Regression: A linear classification algorithm used to model the relationship between the features and the target variable.
Decision Tree: A non-linear classification algorithm that splits the data into branches to make predictions.
Random Forest: An ensemble method that combines multiple decision trees to improve performance and reduce overfitting.
Gradient Boosting: An ensemble method that builds trees sequentially, with each tree trying to correct the errors of the previous one.

# Data Exploration:
The notebook includes data exploration using histograms, scatter plot matrices, and a correlation matrix to 
visualize the relationships between features and the target variable.

# Data Preprocessing:
The data is split into features (sepal length, sepal width, petal length, petal width) and labels (species). 
The dataset is divided into training (80%) and testing (20%) sets using Scikit-learn's train_test_split function.

# Model Evaluation:
The accuracy scores of each model on the test data are reported:

Logistic Regression: Accuracy varies based on the dataset's scaling, with liblinear used as the solver.
Decision Tree: May suffer from overfitting on this small dataset.
Random Forest: Achieves high accuracy due to ensemble learning with a small number of trees (3).
Gradient Boosting: Achieves 100% accuracy even with one estimator, possibly due to the small dataset.
Note: The achieved accuracy scores should be taken with caution and may vary depending on the dataset size, preprocessing steps, and hyperparameter tuning.

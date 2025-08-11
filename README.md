# AI-ML-Task-5

## Decision Trees and Random Forests

## Overview
This project focuses on implementing tree-based machine learning models for classification tasks. The main objectives include training and visualizing decision trees, analyzing overfitting by controlling tree depth, training random forests, interpreting feature importances and evaluating model performance using cross-validation.

## Dataset
The dataset used is the Heart Disease dataset (heart.csv), which contains 1025 samples with 14 features related to patient health, including a binary target indicating the presence or absence of heart disease.

## Tools and Libraries
Python

Pandas

Scikit-learn

Matplotlib

Graphviz

## Steps

1. Import the Dataset
Load the dataset using Pandas and explore basic information such as data types and missing values.

2. Data Preparation
Separate features and the target variable. Split the dataset into training and testing sets using a train-test split.

3. Train a Decision Tree Classifier and Visualize the Tree
Train a decision tree classifier with a specified maximum depth. Visualize the trained decision tree using Graphviz.

4. Analyze Overfitting and Control Tree Depth
Train decision trees with varying depths to analyze how tree complexity affects training and testing accuracy. Visualize accuracy trends over different depths.

5. Train a Random Forest and Compare Accuracy
Train a random forest classifier with multiple estimators. Compare training and testing accuracy to that of the decision tree to check for improvement and reduction in overfitting.

6. Interpret Feature Importances
Extract and visualize feature importances from the random forest model to understand which features contribute most to the prediction.

7. Evaluate Using Cross-Validation
Use k-fold cross-validation (k=5) to evaluate the stability and robustness of the random forest model.

## Output
1. Visualized decision tree saved as decision_tree.pdf
2. Accuracy scores printed for training and testing datasets for both models
3. Feature importance bar chart displayed
4. Cross-validation scores and their mean are printed


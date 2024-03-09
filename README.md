# Titanic Prediction 

## Overview
This repository contains the code and data for the Titanic prediction task, where the goal is to predict whether passengers survived or not based on various features. In this task, we perform data cleaning to handle missing values, conduct exploratory data analysis (EDA), remove outliers, and build predictive models using logistic regression, random forest, support vector machine (SVM), and gradient boosting algorithms. Additionally, we visualize the ROC curve to evaluate model performance.

## Contents
- `Titanic_prediction.ipynb`: Jupyter Notebook containing the code for data cleaning, EDA, outlier removal, model building, and ROC curve visualization.
- `Titanic-Dataset.csv`: Dataset containing information about Titanic passengers.
- `README.md`: This file, providing an overview of the project.

## Data Cleaning
- Handled missing values in the dataset using appropriate techniques such as imputation.
- Ensured consistency and correctness of data types.

## Exploratory Data Analysis (EDA)
- Conducted EDA to understand the distribution and relationships between variables.
- Utilized pairplot, boxplot, and countplot to visualize data distributions and correlations.
- Derived insights from EDA to inform feature selection and model building.

## Outlier Removal
- Identified and removed outliers from the dataset using statistical methods or domain knowledge.
- Ensured that outlier removal did not significantly impact the integrity of the dataset.

## Model Building
- Implemented logistic regression, random forest, SVM, and gradient boosting models for predicting passenger survival.
- Tuned hyperparameters where necessary to optimize model performance.
- Evaluated models using appropriate metrics such as accuracy, precision, recall, and F1-score.

## ROC Curve Visualization
- Plotted ROC curves for each model to visualize their performance in terms of true positive rate (sensitivity) and false positive rate (1 - specificity).
- Calculated the area under the ROC curve (AUC) to quantify the discriminatory power of the models.

## Conclusion
This project demonstrates the process of data cleaning, exploratory data analysis, outlier removal, and predictive modeling for the Titanic prediction task. By leveraging various machine learning algorithms and evaluation techniques, we aim to accurately predict passenger survival based on available features.

For detailed implementation and results, refer to the `titanic_prediction.ipynb` notebook.


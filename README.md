# Diabetes Classification Project

## Introduction

This project aims to classify whether a patient has diabetes based on health conditions such as glucose level, blood pressure, age, etc. The objective is to provide insights into which features are most impactful in predicting the disease, as well as to compare the performance of different machine learning algorithms in making the predictions.

## Contents

- `features.txt`: A file describing the features used in the model.
- `requirements.txt`: Lists all Python libraries required for this project.
- `diabetes.ipynb`: Jupyter Notebook containing the code for Exploratory Data Analysis (EDA), model training, evaluation, and conclusion.


## Overview

This project utilizes a dataset from Kaggle, containing various health metrics to predict the onset of diabetes. The dataset can be accessed [here](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).

## Methodology

1. **Data Preprocessing**: Checked for missing values and outliers in the dataset.
2. **Exploratory Data Analysis (EDA)**: Used visualizations to understand the distribution and relationship of features.
3. **Oversampling**: Used SMOTE to balance the dataset.
4. **Model Training and Evaluation**: The following classifiers were used:
    - Logistic Regression
    - Random Forest
    - XGBoost
    - SVM
    - K-Nearest Neighbors
    - Naive Bayes
    - Decision Tree
    - AdaBoost
5. **Model Comparison**: Performed 10-fold cross-validation to evaluate the performance of each model.

## Conclusion

The models were trained and evaluated using metrics such as accuracy, confusion matrix, and a classification report. Among the classifiers, Random Forest had the highest accuracy and is recommended for predicting diabetes in new patients.

## Instructions

1. Clone this repository to your local machine.
2. Navigate to the project directory and install the required packages using `pip install -r requirements.txt`.
3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) and place it in the project directory.
4. Open `diabetes.ipynb` in Jupyter Notebook and run all cells to see the models in action.


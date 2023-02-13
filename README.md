# Breast Cancer Diagnosis using Machine Learning
## Table of Contents

    Introduction
    Data Import and Preprocessing
    Exploratory Data Analysis
    Feature Selection
    Model Selection and Training
    Model Evaluation

## Introduction

This project aims to diagnose breast cancer using machine learning techniques. The dataset used for this project is from Wisconsin Breast Cancer Diagnostic (WDBC) and contains diagnosis results for 569 patients along with the features such as radius, texture, perimeter, etc. The goal is to predict whether the diagnosis is benign or malignant using these features.
## Data Import and Preprocessing

The data is imported into the python environment using the pandas library and missing values are handled by dropping the rows with NaN values. The categorical features are then encoded into numerical values using the LabelEncoder class.
## Exploratory Data Analysis

The target variable 'diagnosis' is analyzed using a count plot and the correlation between features is visualized using a heatmap.
## Feature Selection

Chi-Squared test is used to select the top 10 features that contribute to the prediction of breast cancer diagnosis. These selected features are then used for training the models.
## Model Selection and Training

Two models, Logistic Regression and Decision Tree Classifier, are trained on the selected features and their accuracy is measured using cross-validation and testing.
## Model Evaluation

The final accuracy of both models is compared and the best one is selected for making predictions.

### Note: The code was run on python version 3.x with the libraries pandas, numpy, matplotlib, seaborn, sklearn, etc.

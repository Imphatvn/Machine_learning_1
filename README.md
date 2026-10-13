# Obesity Level Classification with Machine Learning

A machine-learning classification project that predicts obesity categories
using demographic, physical, and lifestyle-related variables.

This repository contains my portfolio implementation and documentation,
developed from coursework completed in Machine Learning I at NOVA IMS.

## Objective

Classify individuals into seven weight and obesity categories using
features such as age, height, weight, physical activity, eating habits,
and other lifestyle variables.

## Approach

- Exploratory data analysis and data-quality checks
- Missing-value handling and categorical-variable encoding
- Feature engineering, including BMI
- Feature selection using RFE and mutual information
- Model comparison and hyperparameter tuning
- Final ensemble using Logistic Regression, Random Forest, and Gradient Boosting

## Results

The final voting classifier achieved a macro F1-score of 0.95 on the
held-out internal evaluation set.

## Important note

This is an academic machine-learning project, not a clinical diagnostic
tool. Because the implementation includes weight, height, and BMI-derived
features, results should not be interpreted as prediction of future
obesity risk from lifestyle information alone.

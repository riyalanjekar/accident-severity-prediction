# Road Accident Severity Prediction

## Overview
This project was completed as part of my MSc in Business Analytics at Aston University. It uses machine learning to predict road accident severity from accident and vehicle data.

## Objective
To develop and evaluate classification models for accident severity, considering the challenges of imbalanced data.

## Dataset
The analysis combines accident and vehicle datasets using the shared Accident_Index identifier.

## Methodology
- Exploratory data analysis to understand patterns and data quality.
- Data preprocessing, including missing-value treatment and categorical encoding.
- Feature engineering and feature selection.
- Stratified train-test splitting to preserve class proportions.
- Model development using Decision Tree and Random Forest classifiers.
- Hyperparameter tuning using cross-validation.

## Model Evaluation
Models were compared against a majority-class baseline using:
- Accuracy
- Macro precision
- Macro recall
- Macro F1-score
- Confusion matrices

Macro-averaged metrics were used to assess performance across severity classes, given the imbalanced target distribution.

## Tools
Python, pandas, NumPy, scikit-learn, Matplotlib and seaborn.

## How to Run
1. Download the project notebook.
2. Open it in Jupyter Notebook or Google Colab.
3. Make the required datasets available and update the file paths.
4. Install the packages imported in the notebook.
5. Run the cells in order.

## Author
Riya Lanjekar
MSc Business Analytics, Aston University

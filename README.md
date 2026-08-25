# UFC Fight Outcome Prediction

A machine learning project using historical UFC fighter statistics to predict fight outcomes.

## Overview

The goal of this project was to investigate whether fighter statistics could be used to predict the winner of a UFC fight. The project involved cleaning and exploring fight data, selecting relevant features, training classification models, tuning model parameters, and comparing their performance.

## Methods

- Data cleaning and preprocessing with pandas
- Exploratory data analysis and visualization
- Feature selection and engineering
- Feature standardization
- K-Nearest Neighbors (KNN) classification
- KNN hyperparameter tuning
- Logistic Regression
- Train/test evaluation using classification accuracy

## Results

After testing KNN models with different values of k, the best-performing model used **k = 18**.

- **KNN Accuracy:** 68.7%
- **Logistic Regression Accuracy:** 71.1%

Logistic Regression produced the highest test accuracy.

## Technologies

- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Jupyter / Google Colab

## Notebook

The complete analysis, model development, and results are available in `ufc_fight_prediction.ipynb`.

# ML-Football-Match-Predictor

## Overview
This project leverages Machine Learning techniques to predict the outcome of football matches based on historical data. It is part of the challenge **"Football : Qui va gagner ?"** organized by QRT.

## Data Source
The dataset for this project is provided as part of the challenge. It includes `X_train` and `X_test` datasets, accessible here: [Challenge Data](https://challengedata.ens.fr/participants/challenges/143/).

## Data Preprocessing
To prepare the data for modeling, the following preprocessing steps were applied:
- **Normalization**: Ensuring consistent scales across features.
- **Handling Missing Values**: Addressing incomplete or missing data to improve model reliability.

## Model Selection
The project explores and compares three classification models to predict match outcomes:
1. **XGBoost**
2. **Random Forest**
3. **Decision Tree**

The notebook provides a detailed explanation of all the steps followed for training, fitting, and evaluating these models.
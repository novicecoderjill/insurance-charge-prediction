# Insurance Charge Prediction

## Project Overview

This project aims to predict insurace charges based on a set of features, such as age, gender, BMI and other factors. The goal is to create a machine learning model that can accurately estimate the charges for a given individual based on their profile.

## Dataset
The dataset used for this project is `insurance.csv`. It includes the following featues:
- `age`: Age of the individual
- `sex`: Gender
- `BMI`: Body Mass Index
- `children`: Number of children
- `smoker`: Whether the individual is a smoker
- `region`: The region where the individual resides
- `charges`: Medical insurance charges (target variable)

## Data Preprocessing

The preprocessing pipeline includes the following steps:

- Handling duplicated rows
- Handling missing values
- Correcting datatype
- Encoding categorical variables (sex, smoker, region)
- Feature scaling (StandardScaler for age, bmi, charges)

## Modeling
Linear Regression

## Evaluation 
- R-squared (R²)

## Validation
- Model was validated with a new dataset called `validation_dataset.csv`

## The results
The mean R-squared scores across 5 folds is 0.75. This suggests a good level of predictive power, but may be further improved with hyperparameter tuning, feature engineering and exploring different model architectures.

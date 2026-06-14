# Data Preprocessing Report

## Dataset
Titanic Dataset

## Exploratory Data Analysis (EDA)
Performed initial analysis to identify:
- Missing values
- Data types
- Data distribution

## Missing Value Handling
- Age: Median Imputation
- Fare: Median Imputation
- Embarked: Mode Imputation

## Categorical Encoding
- Sex: Label Encoding
- Embarked: One-Hot Encoding

## Feature Engineering
Created a new feature:
FamilySize = SibSp + Parch

## Feature Scaling
Applied StandardScaler to:
- Age
- Fare
- FamilySize

## Data Leakage Prevention
Scaling parameters were fitted only on training data and then applied to test data.

## Result
Generated a clean, machine-learning-ready dataset saved as processed_dataset.csv.
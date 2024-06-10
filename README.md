# Salary Prediction of Data Professions

## Overview
This project aims to predict the salary of data professionals based on various features such as age, gender, designation, past experience, etc. The dataset contains information about data professionals including their personal details, work-related information, and salary.

## Dataset
The dataset consists of the following columns:
- FIRST NAME: First name of the data professional
- LAST NAME: Last name of the data professional
- SEX: Gender of the data professional
- DOJ: Date of joining the company
- CURRENT DATE: Current date of data
- DESIGNATION: Job role/designation
- AGE: Age of the data professional
- SALARY: Target variable, the salary of the data professional
- UNIT: Business unit or department
- LEAVES USED: Number of leaves used
- LEAVES REMAINING: Number of leaves remaining
- RATINGS: Ratings or performance ratings
- PAST EXP: Past work experience

## Exploratory Data Analysis (EDA)
- Loaded the dataset using pandas.
- Cleaned the data by handling missing values and duplicates.
- Conducted basic data exploration to understand the distribution and relationship of variables.
- Visualized data using various plots such as scatter plots, box plots, and bar plots.

## Feature Engineering
- Encoded categorical variables using LabelEncoder and OneHotEncoder.
- Standardized numerical variables using StandardScaler.

## Model Development
- Split the dataset into training and testing sets.
- Constructed a pipeline for data preprocessing and model training.
- Trained a Linear Regression model to predict salaries.
- Evaluated the model's performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2).

## Results
- Linear Regression Performance:
  - MAE: 0.1101
  - MSE: 0.0227
  - RMSE: 0.1505
  - R2: 0.9642

## Files
- `Salary Prediction of Data Professions.csv`: Dataset file
- `salary_prediction.ipynb`: Jupyter Notebook containing code

## Requirements
- Python 3.x
- Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn

## Usage
1. Install the required libraries.
2. Download the dataset file (`Salary Prediction of Data Professions.csv`).
3. Run the Jupyter Notebook `salary_prediction.ipynb` to replicate the analysis and predictions.


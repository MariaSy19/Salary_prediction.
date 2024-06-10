# Salary Prediction for Data Professionals

## Overview

This project aims to predict the salaries of data professionals based on various factors such as experience, job role, department, and performance ratings. The dataset contains information about data professionals, including their demographics, employment details, and salary.

## Dataset Overview

The dataset consists of the following columns:

- `FIRST NAME`: First name of the data professional
- `LAST NAME`: Last name of the data professional
- `SEX`: Gender of the data professional
- `DOJ`: Date of joining the company
- `CURRENT DATE`: Current date of data
- `DESIGNATION`: Job role/designation
- `AGE`: Age of the data professional
- `SALARY`: Target variable, the salary of the data professional
- `UNIT`: Business unit or department
- `LEAVES USED`: Number of leaves used
- `LEAVES REMAINING`: Number of leaves remaining
- `RATINGS`: Performance ratings
- `PAST EXP`: Past work experience

## Key Steps

### 1. Exploratory Data Analysis (EDA)

- Load the dataset and explore its structure.
- Visualize the distribution of variables and identify patterns.
- Analyze relationships between variables and the target variable (salary).

### 2. Data Cleaning and Preprocessing

- Handle missing values by imputation or removal.
- Encode categorical variables and scale numerical features.
- Prepare the data for model training.

### 3. Model Development

- Split the data into training and testing sets.
- Train various machine learning regression models, such as linear regression, decision trees, random forests, and gradient boosting.
- Experiment with different algorithms to find the best-performing model.

### 4. Model Evaluation

- Evaluate the performance of each model using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score.
- Identify the model that provides the most accurate salary predictions.

### 5. ML Pipelines and Model Deployment

- Create ML Pipelines to streamline the end-to-end machine learning process, from data preprocessing to model training.
- Deploy a model that can generate predictions for unseen data using frameworks like Flask or FastAPI.

### 6. Recommendations

- Provide actionable recommendations based on insights from the model.
- Suggestions for factors influencing salaries and potential strategies for improving earnings in data professions.

## Usage

To run the project:

1. Install the required libraries mentioned in `requirements.txt`.
2. Run the Jupyter Notebook or Python script to execute the code.
3. Follow the instructions provided in the code comments for each step of the process.

## Results

- The linear regression model achieved an MAE of X, MSE of Y, RMSE of Z, and R2 score of W, indicating good performance in predicting salaries for data professionals.

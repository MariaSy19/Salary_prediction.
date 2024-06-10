# Predictive Model for Salaries of Data Professionals

## Mission Overview
The goal of this project is to develop a predictive model to estimate the salaries of data professionals. This process involves several key steps: Exploratory Data Analysis (EDA), Feature Engineering, Data Preprocessing, Machine Learning Model Development, Model Evaluation, ML Pipelines and Model Deployment, and providing actionable recommendations based on the model findings.

## Steps

### 1. Exploratory Data Analysis (EDA)
- **Objective**: To understand the data, identify patterns, and derive insights about data professionals' salaries.
- **Tasks**:
  - Load and inspect the dataset.
  - Generate summary statistics for numerical and categorical features.
  - Visualize data to identify trends and patterns.

### 2. Feature Engineering
- **Objective**: To create new features or transform existing ones to enhance model performance.
- **Tasks**:
  - Calculate total experience by combining "Past Experience" with the difference between the current date and the date of joining (DOJ).
  - Measure performance growth rate by dividing performance ratings by past experience.
  - Count the number of projects the employee has worked on.

### 3. Data Preprocessing
- **Objective**: To prepare the data for model training.
- **Tasks**:
  - Handle missing values appropriately.
  - Encode categorical variables.
  - Scale or normalize features as needed.

### 4. Machine Learning Model Development
- **Objective**: To train various machine learning regression models to predict salaries.
- **Tasks**:
  - Experiment with different algorithms such as linear regression, decision trees, random forests, and gradient boosting.
  - Split the data into training and testing sets.
  - Train the models and make predictions.

### 5. Model Evaluation
- **Objective**: To assess the performance of the models using appropriate evaluation metrics.
- **Tasks**:
  - Use metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score.
  - Identify the model that provides the most accurate salary predictions.

### 6. ML Pipelines and Model Deployment
- **Objective**: To streamline the end-to-end machine learning process and deploy the model.
- **Tasks**:
  - Create ML Pipelines to automate the process from data preprocessing to model training.
  - Deploy the model using frameworks like Flask or FastAPI to generate predictions for unseen data.

### 7. Recommendations
- **Objective**: To provide actionable insights and strategies based on model findings.
- **Tasks**:
  - Analyze the factors influencing salaries.
  - Offer recommendations to improve earnings in data professions, such as performance reviews, training, and development, gender pay equity, and role-based salary adjustments.

## Dataset Overview
The dataset contains the following columns:
- `FIRST NAME`: First name
- `LAST NAME`: Last name
- `SEX`: Gender
- `DOJ`: Date of joining the company
- `CURRENT DATE`: Current date of data
- `DESIGNATION`: Job role/designation
- `AGE`: Age
- `SALARY`: Target variable, the salary of the data professional
- `UNIT`: Business unit or department
- `LEAVES USED`: Number of leaves used
- `LEAVES REMAINING`: Number of leaves remaining
- `RATINGS`: Ratings or performance ratings
- `PAST EXP`: Past work experience

## Getting Started
To get started with the project:
1. **Clone the repository**:
   ```sh
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   ```sh
   jupyter notebook
   ```

4. **Start the Flask Application**:
   ```sh
   python app.py
   ```

## Usage
- Use the Jupyter Notebook to perform EDA, feature engineering, and model training.
- The Flask application can be used to deploy the model and generate predictions for new data.

## Contributing
Feel free to open issues or submit pull requests with improvements.

## License
This project is licensed under the MIT License.

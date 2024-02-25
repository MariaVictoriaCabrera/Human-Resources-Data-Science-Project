# Human-Resources-Data-Science-Project
## Overview

This project focuses on predicting employee attrition using data science and machine learning techniques. Employee attrition is a critical challenge in the business world, impacting hiring processes, talent retention, and organizational costs. By leveraging data science approaches, we aim to develop predictive models that can help organizations identify employees who are more likely to leave the company or seek alternative employment.

## Project Objective

The primary goal of this project is to create a predictive model that can accurately forecast the likelihood of an employee leaving the company. By utilizing machine learning algorithms and analyzing relevant features, we aim to provide valuable insights for HR departments to make informed decisions and reduce the costs associated with employee turnover.

## Data Source

The dataset used for this project is sourced from Kaggle: [IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset). It includes various attributes such as age, job role, education, and satisfaction levels, among others.

## Hypothesis and Research Interests

**Hypothesis:**
- Employees with lower job satisfaction, longer commuting distances, and fewer years at the company may be more prone to attrition.

**Research Interests:**
1. Explore the impact of job satisfaction on employee retention.
2. Investigate the correlation between commuting distance and attrition.
3. Analyze the role of years of experience at the company in predicting attrition.

## Data Cleaning and Preprocessing

1. Removed irrelevant columns such as 'EmployeeCount', 'Over18', and 'StandardHours'.
2. Encoded categorical variables using one-hot encoding.
3. Handled missing or inconsistent data.

## Exploratory Data Analysis (EDA)

1. Visualized the distribution of key features.
2. Explored relationships between variables.
3. Investigated the imbalance in the target variable 'Attrition'.

## Model Development

1. Utilized machine learning models such as Logistic Regression.
2. Experimented with adjusting class weights to handle class imbalance.
3. Evaluated model performance using metrics like precision, recall, and F1-score.

## Dependencies

- Python 3.x
- Libraries: pandas, numpy, scikit-learn, seaborn, matplotlib, plotly.express

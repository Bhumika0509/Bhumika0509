# HR Analytics - IBM Employee Attrition Analysis

## Project Overview

This project aims to analyze employee attrition at IBM using data analytics techniques. The goal is to identify key factors contributing to employee turnover and provide insights that could help the HR department reduce attrition rates. The analysis uses data visualizations, machine learning models, and statistical tests to uncover trends and relationships between employee characteristics and their likelihood of leaving the company.

## Dataset

The dataset used in this project contains employee records from IBM, with various attributes such as:
- **Employee Demographics**: Age, Gender, Marital Status, Education
- **Job-related Attributes**: Job Role, Department, Years at Company, Years in Current Role
- **Compensation and Benefits**: Monthly Income, Stock Option Level, OverTime
- **Satisfaction Metrics**: Job Satisfaction, Environment Satisfaction, Work-Life Balance

The dataset is well-suited for attrition analysis because it includes key variables that might influence an employee's decision to leave.

## Project Objectives

The key objectives of this analysis are:
1. To identify the significant factors affecting employee attrition at IBM.
2. To develop predictive models that can classify employees who are likely to leave the organization.
3. To offer data-driven recommendations for reducing employee turnover.

## Analysis Techniques

The project includes the following key steps and techniques:
- **Data Cleaning & Preprocessing**: Handling missing values, transforming categorical variables into numerical formats, and standardizing data.
- **Exploratory Data Analysis (EDA)**: Visualizing the relationships between employee attributes and attrition using histograms, bar charts, and heatmaps.
- **Feature Engineering**: Selecting relevant features for modeling and testing their correlations with attrition.
- **Machine Learning Models**:
  - **Logistic Regression**: For binary classification to predict attrition.
  - **Random Forest Classifier**: To capture nonlinear relationships and improve prediction accuracy.
  - **XGBoost Classifier**: A powerful model for robust and efficient attrition predictions.
- **Model Evaluation**: Assessing model performance using metrics like accuracy, precision, recall, and F1-score.

## Results

The analysis revealed several key factors contributing to employee attrition, including:
- **Job Role and Work Environment**: Employees in certain roles were more likely to leave due to dissatisfaction with job-related aspects like overtime and workload.
- **Salary and Compensation**: Employees with lower income and stock options had a higher likelihood of leaving the company.
- **Work-life Balance**: Poor work-life balance showed a strong correlation with higher attrition rates.
  
The Random Forest and XGBoost models provided the best accuracy in predicting employee attrition, with accuracy scores of over 80%.

## Conclusion

The analysis highlights critical areas where IBM can focus to reduce employee turnover, including improving work-life balance, offering competitive salaries, and addressing dissatisfaction in specific job roles. By implementing data-driven strategies based on the findings, IBM's HR team can proactively manage and reduce employee attrition.

## Technologies Used

- **Python**: For data manipulation and analysis
- **Pandas & NumPy**: For data preprocessing
- **Matplotlib & Seaborn**: For visualizing the data
- **Scikit-learn**: For machine learning model implementation
- **XGBoost**: For boosting model performance
- **Google Colab**: For project development and execution

## How to Run the Project

1. Clone the repository: 
   ```bash
   git clone https://github.com/Bhumika0509/HR_Analysis_IBM.git

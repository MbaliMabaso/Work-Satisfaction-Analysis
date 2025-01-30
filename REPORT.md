📊 Report

1️⃣ Introduction
Employee satisfaction is a critical factor influencing productivity, retention, and overall organizational success. This project investigates key predictors of work satisfaction, leveraging survey data and statistical modeling.

2️⃣ Research Question
What are the most significant factors influencing employee job satisfaction, and how well can we predict satisfaction using these variables?

3️⃣ Data Overview
Dataset: Employee survey responses from kaggle.com.
Sample Size: 3,025 employees.
Key Variables:
Independent Variables: Gender,Age, Marital Status, Job Level, Experience, Department, Employment type, Work life balance, Work environment, physical activity hours, Workload,
Stress, Sleep hours, Commute mode, Commute distance, Number of companies worked for, Team size, Number of reports, Educational level, Have over-time, Training hours per year.
Dependent Variable: Job Satisfaction. 

4️⃣ Exploratory Data Analysis (EDA)
- Missing Data: No significant missing values detected.
- Correlation Analysis: Work life balance, Work environment and sleep hours had positive correlations with job satisfaction. Stress and work load had negative correlations with
  job satisfaction. The correlations were small, ranging from .18 to .260.
  ![image alt]([image_url](https://github.com/MbaliMabaso/Work-Satisfaction-Analysis/blob/2e26dbdedf4ebe1d38c7261e933f69116befd3c4/EmployeeSurveyHeatMap.png))
- Multicollinearity: Sleep hours had a VIF > 10, therefore, it was removed from the model.
   ![image alt]([image_url]([)](https://github.com/MbaliMabaso/Work-Satisfaction-Analysis/blob/95ef4692b651160a3c0d2af6429722fb15ebfb09/EmployeeSurveyVIF.png)

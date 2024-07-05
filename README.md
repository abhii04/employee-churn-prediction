# Employee Turnover Prediction Project

## Overview
This project focuses on predicting employee turnover using machine learning techniques. Employee turnover, or churn, is a critical issue for organizations as it impacts productivity and morale. By predicting turnover, companies can proactively take steps to retain valuable employees.

![image](https://github.com/abhii04/employee-churn-prediction/assets/138236906/b2ec6d3b-7614-4d36-93a9-4c521d506f2f)


## Dataset
The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/). It includes various attributes that can influence turnover such as:
- Satisfaction Level
- Evaluation Scores
- Number of Projects
- Average Monthly Hours
- Years at the Company
- Work Accidents
- Promotions in the Last 5 Years
- Department
- Salary Level

## Goal
The primary goal of this project is to build and evaluate machine learning models that can accurately predict whether an employee is likely to leave the company (turnover prediction). This helps in identifying factors that contribute to turnover and developing strategies to mitigate it.

## Methodology
1. **Data Preprocessing:**
   - Handling missing values
   - Encoding categorical variables (One-Hot Encoding)
   - Feature scaling

2. **Exploratory Data Analysis (EDA):**
   - Visualizing distributions of features
   - Correlation analysis
   - Identifying relationships between features and turnover

3. **Model Building:**
   - Utilizing various machine learning algorithms:
     - Logistic Regression
     - Random Forest
     - Gradient Boosting
     - Support Vector Machines (SVM)
     - Neural Network

4. **Evaluation Metrics:**
   - Accuracy, Precision, Recall, F1-score
   - ROC-AUC Curve and Score

## Results
- Detailed evaluation results for each model:
  - Confusion matrices
  - Classification reports
  - ROC-AUC scores

## Conclusion
- This project on predicting employee turnover provides valuable insights into the factors influencing employee retention within an organization. By leveraging a combination of data preprocessing, machine learning models, and visualization techniques, we have identified key predictors of employee turnover such as job satisfaction, years at the company, and project count.

- The analysis revealed that:

- Job Satisfaction: The most critical factor influencing turnover, highlighting the importance of employee morale and engagement.
- Years at Company: Tenure significantly impacts turnover, with longer tenure correlating with lower turnover rates.
- Project Count: The number of projects an employee is involved in affects turnover, indicating that workload and task management are essential considerations.
- The development of a predictive model using Random Forest and other machine learning algorithms demonstrated the feasibility and effectiveness of forecasting employee turnover. This predictive capability allows organizations to proactively address retention issues, improve employee satisfaction, and optimize resource management.

Further improvements can be made by incorporating additional features, experimenting with different modeling techniques, and enhancing the application with user-friendly interfaces such as a Streamlit app. Overall, this project serves as a foundation for building more sophisticated HR analytics tools aimed at reducing employee turnover and fostering a more stable and productive workforce.








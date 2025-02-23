# SyriaTel-Customer-Churn-Prediction

## Overview

The problem identified is customers are leaving (churning), and the company wants to predict and reduce this.The main goal is to build a model to identify customers at risk of churning so the company can take action. Business impact will be reducing churn to improve customer retention and aid the company in reducing howmuch money was lost because of customers who churned.


## Data Understanding

The dataset used in this project is [Data Source](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset).

The dataset: Includes customer details, call charges, service usage, and churn status.
Key features: Call charges, customer service calls, account length, etc.
Initial insights: Some features (e.g., high service calls) show patterns related to churn.

The main variable of interest is **churn**.


## Modeling

The libraries used were: pandas, numpy, matplotlib, seaborn, scikit-learn
1. Handling Imbalanced Data: The project implements techniques to help handle imbalanced data such as SMOTE, ensuring accurate predictions even when the dependent variable is underrepresented.
2. Exploratory Data Analysis (EDA): The project features a stage of Exploratory Data Analysis (EDA), where we examine the data closely to identify trends and understand the reasons behind customer churn.
3. Classification: The project employs a 2 models, i.e Logistic Regression and Random Forest, to predict customer churn, with techniques such as class weighting and SMOTE used to handle class imbalance.


## Evaluation

| Model                   | Accuracy | Recall Score | F1 Score |
|-------------------------|----------|--------------|----------|
| Logistic Regression     | 0.718141 | 0.782178     | 0.456647 | 
| Random Forest           | 0.941529 | 0.772277     | 0.799999 | 


## Conclusion

The Random Forest model is the best choice because it predicts customer churn more accurately and helps us understand which factors influence customers to leave. This will allow us to take better actions to reduce churn.


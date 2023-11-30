# Tel-Customer-Churn

![Company Logo](https://github.com/Mbachia/Tel-Customer-Churn/raw/main/Company%20Logo/download.png)

## SyriaTel Customer Churn Analysis

# Overview

SyriaTel is a telecommunications company in Syria. They have been informed that some of their customers have started to churn, discontinue their service. This analysis will determine what features will indicate if a customer will discontinue their service.

## Problem Statement
Syria Tel, a prominent telecom company, grapples with a pressing issue—customer churn. This means customers are stopping their services with Syria Tel, affecting the company's stability and income. The problem lies in predicting when customers might leave and understanding why they choose to do so. Syria Tel wants to prevent this from happening and keep their customers satisfied.

## Main Objective
To apply classification modeling techniques to analyze customer churn data for Syria Tel, aiming to identify and quantify the influential factors contributing to customer attrition. This analysis will enable stakeholders to make data-informed decisions regarding customer retention strategies and optimize efforts to minimize churn in the telecom industry.

## Subjective Objectives
1. Explore the Data for Classification
Explore the dataset to understand the relationships between different variables and the target variable (customer churn).

2. Create a Classification Model for Churn Prediction
Build a classification model (such as Logistic Regression, Random Forest, or XGBoost) to predict customer churn. 

3. Analyze Feature Importance and Effects
Analyze the importance of independent features in predicting churn. Identify the most influential factors affecting churn prediction based on the model's coefficients, feature importance scores, or other relevant metrics.

4. Assess Model Performance and Reliability
Evaluate the classification model's performance through metrics like accuracy, precision, recall, and confusion matrix. Ensure the model is reliable and accurately predicts customer churn by testing.

5. Offer Practical Insights and Recommendations
Provide actionable insights and recommendations based on the classification model's findings. Offer guidance to telecom companies on factors influencing customer churn.

## Data Understanding

The dataset has the following columns:

state, account length,area code,phone number,international plan,voice mail plan, number vmail messages,total day minutes,total day calls,total day charge, total eve minutes, total eve calls,total eve charge, total night minutes,total night calls,total night charge,total intl minutes,total intl calls,total intl charge,customer service calls,churn.

# Results and interpretation

## Baseline Model:

Accuracy:
The accuracy of the model is 87.03%. This metric signifies the overall correctness of predictions made by the model. In this case, the model correctly predicted approximately 87 out of every 100 instances, which seems reasonably high at first glance.

## Random Forest Classifier:

Accuracy:
The accuracy of the model is 89.40%. Similar to the previous case, this metric represents the overall correctness of predictions made by the model. It correctly predicted approximately 89 out of every 100 instances, showing a slightly higher accuracy compared to the previous model.

After tuning Best Parameters Found: The best combination of parameters for your model that resulted in the highest accuracy on your training data are:
'max_depth': None (meaning no maximum depth for the trees was set)
'min_samples_split': 2 (the minimum number of samples required to split a node was set to 2)
'n_estimators': 200 (the number of trees in the forest was set to 200)

After tuning the model with these parameters, it achieved an accuracy of approximately 89.80% on the test data. This means that the model correctly predicted almost 90 out of every 100 instances, showcasing improved performance compared to default settings or other parameter combinations.

## XGBoost Classifier
The accuracy of the model is 91.24%. This indicates the overall correctness of predictions made by the model. It correctly predicted approximately 91 out of every 100 instances, showcasing a higher accuracy compared to previous models.





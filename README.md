# Tel-Customer-Churn

SyriaTel Customer Churn Analysis

Overview
SyriaTel is a telecommunications company in Syria. They have been informed that some of their customers have started to churn, discontinue their service. This analysis will determine what features will indicate if a customer will discontinue their service.

Business Understanding
Introduction
In the dynamic realm of telecommunications, Syria Tel grapples with the pervasive challenge of customer churn. This project represents a concerted effort to decode the intricate patterns and drivers behind customer attrition within Syria Tel's subscriber base. By harnessing advanced machine learning methodologies, the aim is to discern critical indicators and behavioral trends leading to customer churn.

The core objective revolves around constructing a predictive model adept at foreseeing potential churn instances, equipping Syria Tel with actionable insights to preemptively engage and retain customers. Beyond prediction, the project endeavors to furnish actionable strategies, empowering Syria Tel's stakeholders with data-driven interventions to refine service quality, foster enduring customer relationships, and fortify the company's competitive stance in the telecommunications landscape. Through this exploration, we endeavor to shed light on the enigmatic facets of customer churn, enabling Syria Tel to pivot towards proactive customer retention strategies and sustained growth.

Problem Statement
Syria Tel, a prominent telecom company, grapples with a pressing issue—customer churn. This means customers are stopping their services with Syria Tel, affecting the company's stability and income. The problem lies in predicting when customers might leave and understanding why they choose to do so. Syria Tel wants to prevent this from happening and keep their customers satisfied.

Main Objective
To apply classification modeling techniques to analyze customer churn data for Syria Tel, aiming to identify and quantify the influential factors contributing to customer attrition. This analysis will enable stakeholders to make data-informed decisions regarding customer retention strategies and optimize efforts to minimize churn in the telecom industry.

Subjective Objectives
Explore the Data for Classification
Explore the dataset to understand the relationships between different variables and the target variable (customer churn). Identify relevant features that may influence churn, considering categorical and numerical variables.

Create a Classification Model for Churn Prediction
Build a classification model (such as Logistic Regression, Random Forest, or XGBoost) to predict customer churn. Choose appropriate independent variables (features) that are likely to impact churn, considering factors like international plan usage, call minutes and customer service calls>

Analyze Feature Importance and Effects
Analyze the importance of independent features in predicting churn. Identify the most influential factors affecting churn prediction based on the model's coefficients, feature importance scores, or other relevant metrics.

Assess Model Performance and Reliability
Evaluate the classification model's performance through metrics like accuracy, precision, recall, and confusion matrix. Ensure the model is reliable and accurately predicts customer churn by testing.

Offer Practical Insights and Recommendations
Provide actionable insights and recommendations based on the classification model's findings. Offer guidance to telecom companies on factors influencing customer churn. Highlight influential features and their impact on churn, enabling better decision-making for retaining customers, optimizing service plans, or improving customer service.

Data Understanding

The dataset has the following columns:

state: the state the customer lives in

account length: the number of days the customer has had an account

area code: the area code of the customer

phone number: the phone number of the customer

international plan: true if the customer has the international plan, otherwise false

voice mail plan: true if the customer has the voice mail plan, otherwise false

number vmail messages: the number of voicemails the customer has sent

total day minutes: total number of minutes the customer has been in calls during the day

total day calls: total number of calls the user has done during the day

total day charge: total amount of money the customer was charged by the Telecom company for calls during the day

total eve minutes: total number of minutes the customer has been in calls during the evening

total eve calls: total number of calls the customer has done during the evening

total eve charge: total amount of money the customer was charged by the Telecom company for calls during the evening

total night minutes: total number of minutes the customer has been in calls during the night

total night calls: total number of calls the customer has done during the night

total night charge: total amount of money the customer was charged by the Telecom company for calls during the night

total intl minutes: total number of minutes the user has been in international calls

total intl calls: total number of international calls the customer has done

total intl charge: total amount of money the customer was charged by the Telecom company for international calls

customer service calls: number of calls the customer has made to customer service

churn: true if the customer terminated their contract, otherwise false
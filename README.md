# AI-Powered-Assistant-for-Churn-Prediction

Project Overview

E& AI is an intelligent customer churn prediction system designed to help marketing and customer retention teams identify customers who are at risk of leaving a telecom service. The solution combines a Large Language Model (LLM), machine learning, and explainable AI techniques to transform natural language customer descriptions into actionable business insights.

The system allows marketing employees to describe a customer using plain English rather than manually entering structured data. A Llama 3.2 model extracts the relevant customer attributes and converts them into a structured JSON format. These features are then processed and passed to a trained XGBoost classification model, which predicts the probability of customer churn.

To improve transparency and trust, SHAP (SHapley Additive exPlanations) is used to identify the most influential factors contributing to each prediction. Based on the churn probability and key risk drivers, the system automatically generates business-oriented recommendations and retention strategies tailored to the customer's risk level.

The solution is exposed through a FastAPI backend and can be integrated with a web-based frontend, enabling marketing teams to quickly assess churn risk, understand the reasons behind predictions, and take proactive retention actions.

Key Features
Natural Language Customer Analysis using Llama 3.2
Automated Feature Extraction and Validation
Customer Churn Prediction using XGBoost
Explainable AI using SHAP
Business-Oriented Risk Assessment
Automated Retention Recommendations
FastAPI REST API Integration
Real-Time Prediction and Reporting
System Workflow
A marketing employee enters a customer description in natural language.
The LLM extracts relevant customer attributes and generates structured JSON.
The backend validates and preprocesses the extracted features.
The XGBoost model predicts the customer's churn probability.
SHAP identifies the most important factors influencing the prediction.
A business report containing risk level, key factors, and recommendations is generated.
Results are returned to the frontend for decision-making.
Technologies Used:
HTML
CSS
JS
Python
FastAPI
NGrok
XGBoost
SHAP
Llama 3.2 (Unsloth)
Pandas
Joblib
Uvicorn
Ngrok

E& AI enables marketing and retention teams to proactively identify at-risk customers, understand the primary reasons behind churn predictions, and apply targeted retention strategies. By combining predictive analytics with explainable AI and natural language processing, the system reduces manual analysis effort and supports data-driven customer retention decisions.
# Business Value
This project enables marketing and retention teams to proactively identify at-risk customers, understand the primary reasons behind churn predictions, and apply targeted retention strategies. By combining predictive analytics with explainable AI and natural language processing, the system reduces manual analysis effort and supports data-driven customer retention decisions.

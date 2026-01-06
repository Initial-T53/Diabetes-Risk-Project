README — Diabetes Prediction Project
Business Problem
Primary care providers often struggle to identify high‑risk patients early because lifestyle behaviors are inconsistently reported and patients are seen infrequently. This leads to missed opportunities for early intervention and delays in diagnosing diabetes.
Goal
Develop a machine learning model that predicts diabetes diagnosis at the time of a routine check‑up using demographic, lifestyle, and metabolic indicators.
Value
- Flag patients who may benefit from additional lab testing
- Support preventive health and early‑intervention programs
- Reduce long‑term healthcare costs associated with diabetes
Deliverables
- Machine learning models with feature importance
- SHAP interpretability dashboard
- Risk stratification tool

Dataset Description
- Source: Kaggle — Diabetes Health Indicators Dataset by Mohan Krishna Thalla
- Shape: 100,000 rows × 31 columns
- Variable categories (8 types):
- Demographic
- Socioeconomic
- Lifestyle & Behavior
- Medical History
- Anthropometric & Vital Signs
- Lipid Profile
- Metabolic Indicators
- Target Variable
- Target Variable: Diagnosed_diabetes — indicates whether a patient has diabetes.

Methodology / Workflow Overview
- Raw EDA
- Data Cleaning
- EDA Phase 2
- Data Preparation
- Model Development
- Evaluation Metrics
- Model Interpretability
- Risk Stratification

Modeling Approach
Models Tested
- Logistic Regression
- Random Forest Classifier
- XGBoost
Evaluation Metrics
- ROC‑AUC
- Precision
- Recall
- F1 Score
- Accuracy
- Confusion Matrix
Final Model Selection
The Random Forest Classifier was selected because it produced the lowest number of false positives (patients incorrectly predicted as diabetic).
Class Balance
The dataset has a 60/40 split between diabetic and non‑diabetic patients.
This imbalance reflects the dataset’s underlying population, so no resampling or class‑weight adjustments were applied.

Interpretability Summary
- SHAP values were used to understand how each feature influences the prediction.
- Interpretability is essential for understanding which variables contribute most strongly to diabetes risk.
- Key insights:
- HbA1c
- Fasting glucose
- Postprandial glucose
These metabolic indicators were the strongest predictors of diabetes.

Risk Stratification Tool
- Risk categories:
- Low: 0–33% predicted probability
- Medium: 33.1–66%
- High: 66.1%+
- Intended use: identify high‑risk patients who may benefit from preventive care or follow‑up testing.

project/
│── README.md
│── requirements.txt
│── data/
│── notebooks/
│── report/

How to run dependiencies:
pip install -r requirements.txt
Run notebooks

Future work:
I plan to rerun this project focusing exclusively on lifestyle and behavior variables. My goal is to better understand which modifiable factors have the greatest impact on diabetes risk and how targeted behavioral changes could reduce that risk

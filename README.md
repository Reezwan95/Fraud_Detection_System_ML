# Fraud_Detection_System_ML


# Overview
This project implements a Fraud Detection System using a machine learning pipeline that leverages both supervised learning (XGBoost) and unsupervised learning (K-means, Isolation Forest) to detect fraudulent transactions. The system preprocesses financial transaction data, incorporates anomaly detection features, and evaluates performance using key metrics such as F1-Score, Precision, Recall, and ROC-AUC.

By achieving an F1-score of 92% and a ROC-AUC of 0.96, the system demonstrates robust fraud detection capabilities and reduces false negatives by 15%.


# Features


-Data Preprocessing:

i. Handle missing values using median imputation.
ii. Normalize numerical features with StandardScaler.


-Feature Engineering:

i. Add anomaly detection features using K-means clustering and Isolation Forest.

ii. Machine Learning:

iii. Use XGBoost for supervised classification to identify fraudulent transactions.


-Model Evaluation:

Evaluate using metrics: Precision (95%), Recall (90%), F1-Score (92%), and ROC-AUC (0.96).


-Insights:

Provides actionable insights into improving fraud detection accuracy and reducing false negatives.

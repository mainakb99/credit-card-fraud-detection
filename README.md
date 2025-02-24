# credit-card-fraud-detection

?? Credit Card Fraud Detection
?? Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. Financial fraud is a significant issue worldwide, and this project aims to develop an effective model that can differentiate between legitimate and fraudulent transactions.

?? Objectives
Analyze and preprocess the credit card transaction dataset.
Handle data imbalances using techniques like SMOTE.
Build and evaluate machine learning models to detect fraud.
Optimize performance focusing on Precision, Recall, and F1-score.

?? Dataset
This is a simulated credit card transaction dataset containing legitimate and fraud transactions from the duration 1st Jan 2019 - 31st Dec 2020. It covers credit cards of 1000 customers doing transactions with a pool of 800 merchants.
There are 23 columns altogether,consisting of features like transaction amount,merchant details,customer's personal information,etc.
is_fraud is the Target variable (1 - Fraudulent, 0 - Legitimate)
https://www.kaggle.com/datasets/kartik2112/fraud-detection

?? Tech Stack
Python (Pandas, NumPy, Matplotlib, Seaborn)
Machine Learning: Scikit-Learn, XGBoost
Imbalanced Learning: SMOTE from imblearn
Visualization: Matplotlib, Seaborn
Environment: Jupyter Notebook

?? Approach & Methodology
Data Exploration & Preprocessing

Loaded and optimized dataset for memory efficiency.
Conducted EDA to understand data patterns and fraud distribution.
Addressed class imbalance using SMOTE.
Feature Engineering

Transformed relevant features for better model performance.
Checked for missing values and optimized data types.
Model Building

Tested XGBoost models:
XGBoost
Focused on Recall and Precision due to class imbalance.

Evaluation Metrics:

Confusion Matrix
ROC-AUC Curve
Precision-Recall Curve
Classification Report (Precision, Recall, F1-Score)
?? Results
Model achieved an overall:
 accuracy score of 97%.
 96% Recall and 96% Precision on the test set.
   

?? Challenges Faced
Managing extreme class imbalance.
Ensuring minimal false positives while maximizing fraud detection.
Optimizing model performance without overfitting.

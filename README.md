# 💳 Credit Card Fraud Detection

## 📋 **Project Overview**
This project focuses on detecting fraudulent credit card transactions using **machine learning** techniques. Financial fraud is a significant issue worldwide, and this project aims to develop an effective model that can differentiate between **legitimate** and **fraudulent** transactions.

---

## 🎯 **Objectives**
- 📊 Analyze and preprocess the credit card transaction dataset.  
- ⚖️ Handle data imbalances using techniques like **SMOTE**.  
- 🤖 Build and evaluate machine learning models to detect fraud.  
- 📈 Optimize performance by focusing on **Precision**, **Recall**, and **F1-score**.

---

## 📂 **Dataset**
- **Source**: [Kaggle - Fraud Detection Dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection)  
- **Duration**: 1st Jan 2019 - 31st Dec 2020  
- **Customers**: 1,000 customers performing transactions across 800 merchants  
- **Features**: 23 columns including:
  - Transaction amount  
  - Merchant details  
  - Customer’s personal information  
- **Target Variable**:  
  - `is_fraud`: 1 → Fraudulent, 0 → Legitimate  

---

## 🛠 **Tech Stack**
- **Programming Language**: Python 🐍  
  - Libraries: Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning**:  
  - Scikit-Learn  
  - XGBoost  
- **Imbalanced Learning**:  
  - SMOTE from **Imbalanced-learn**  
- **Visualization**:  
  - Matplotlib  
  - Seaborn  
- **Environment**:  
  - Jupyter Notebook 📓  

---

## 🧠 **Approach & Methodology**

### 📊 **1. Data Exploration & Preprocessing**
- Loaded and optimized the dataset for **memory efficiency**.  
- Conducted **EDA** to understand data patterns and fraud distribution.  
- Addressed **class imbalance** using **SMOTE**.

---

### ⚙️ **2. Feature Engineering**
- Transformed relevant features to boost model performance.  
- Checked and handled **missing values**.  
- Optimized data types for **efficient processing**.

---

### 🤖 **3. Model Building**
- Built and tested **XGBoost** model.  
- Focused on improving **Recall** and **Precision** due to severe class imbalance.  

---

### 📈 **4. Evaluation Metrics**
- ✅ **Confusion Matrix**  
- 📊 **ROC-AUC Curve**  
- 📉 **Precision-Recall Curve**  
- 📝 **Classification Report** (Precision, Recall, F1-Score)  

---

## 🚀 **Results**
- ✅ **Accuracy**: 97%  
- 🔥 **Recall**: 96%  
- 🎯 **Precision**: 96%  

The model effectively identifies fraudulent transactions while maintaining minimal false positives.

---

## ⚡ **Challenges Faced**
- Handling **extreme class imbalance**.  
- Balancing **false positives** while maximizing fraud detection rates.  
- Avoiding **overfitting** while optimizing model performance.

---


---

## 📬 **Contact**
Let's connect and discuss this project further!  
- 💼 **LinkedIn**: https://www.linkedin.com/in/mainak-bhattacharyya-0a29081b5/ (#)  
- 💻 **GitHub**: https://github.com/mainakb99 (#)

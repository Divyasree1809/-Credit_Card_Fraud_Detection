# 💳 Credit Card Fraud Detection using Machine Learning

This project focuses on building a **Machine Learning model** to detect fraudulent credit card transactions using historical transaction data.

The objective is to accurately classify transactions as:

* ✅ **Valid (Normal Transaction)**
* ❌ **Fraudulent Transaction**

Early fraud detection helps financial institutions reduce financial losses and protect customers from suspicious activities.


## 🚀 Project Overview

Fraud detection is a **highly imbalanced classification problem**, where fraudulent transactions represent only a very small fraction of total transactions.

### 🎯 Key Challenges

* Handling **extremely imbalanced dataset** (only 0.02% fraud cases)
* Achieving **high precision** → Minimize false positives
* Achieving **high recall** → Detect maximum fraud cases
* Avoiding misleading high accuracy


## 📊 Dataset Information

Dataset: `creditcard.csv`

* 📦 **Total Transactions:** 284,807
* 🔢 **Total Features:** 31

### Feature Description:

| Feature | Description                             |
| ------- | --------------------------------------- |
| Time    | Seconds elapsed between transactions    |
| V1–V28  | PCA-transformed anonymized features     |
| Amount  | Transaction amount                      |
| Class   | Target variable (0 = Normal, 1 = Fraud) |

Fraud cases represent only **0.02%** of the dataset.


## 🛠️ Technologies & Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn





## 🔎 Interpretation of Results

### ✅ Accuracy: 99.96%

High accuracy due to class imbalance — not reliable alone.

### 🎯 Precision: 98.73%

Very few false positives → Minimal false fraud alerts.

### 🔍 Recall: 79.59%

Model detects ~80% of fraud cases.
Some fraud cases are missed.

### ⚖ F1-Score: 88.14%

Strong balance between precision and recall.

### 📊 MCC: 0.8863

Excellent balanced metric for imbalanced datasets.


## 🔧 Possible Improvements

To further improve fraud detection:

* 🔁 Oversampling (SMOTE)
* 🔻 Undersampling majority class
* 🎯 Adjust class weights
* 🔄 Hyperparameter tuning
* 🚀 Try XGBoost or LightGBM
* 🧠 Use Deep Learning models
* 📊 Feature scaling and feature engineering




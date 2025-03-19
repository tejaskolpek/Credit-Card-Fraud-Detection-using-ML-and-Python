# 🏦 Credit Card Fraud Detection using ML and Python

## 📌 Overview

This project focuses on detecting fraudulent credit card transactions using **Machine Learning (ML)** algorithms. With the increasing number of online transactions, fraud detection has become crucial in financial security. The goal is to develop a model that accurately classifies transactions as **fraudulent or legitimate** by leveraging various machine learning techniques.

## 📂 Dataset

- **Source**: The dataset contains transactions made by European cardholders in September 2013.
- **Size**: 284,807 transactions, including **492 fraudulent cases** (0.172% of total transactions).
- **Features**:
  - `V1` to `V28`: Principal Component Analysis (PCA) transformed features (to ensure confidentiality).
  - `Time`: Seconds elapsed between the first transaction and the respective transaction.
  - `Amount`: The transaction amount.
  - `Class`: The response variable (`0` for **legitimate**, `1` for **fraudulent**).

📌 The dataset has a **severe class imbalance**, requiring specialized techniques for proper model training.

---

## 🚀 Approach & Methodology

### 📊 1. Data Analysis & Preprocessing
✔️ Explored data distribution and correlations.  
✔️ Handled missing values and outliers.  
✔️ Standardized `Amount` and `Time` columns.  

### 🏗️ 2. Machine Learning Models
Implemented multiple ML algorithms for classification:
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree**
- **Random Forest**
- **XGBoost**
- **Support Vector Machine (SVM)**

### 🏋️ 3. Model Validation & Cross-Validation
- Used **Repeated K-Folds** and **Grouped K-Folds** for better generalization.
- Evaluated models using **Precision, Recall, F1-Score, and ROC-AUC**.

### ⚖️ 4. Handling Class Imbalance
- Applied **Synthetic Minority Over-sampling Technique (SMOTE)**.
- Used **ADASYN (Adaptive Synthetic Sampling)** for further balancing.

---

## 📈 Performance Metrics

Evaluated models based on:
✔️ **Accuracy**  
✔️ **Precision & Recall** (to balance false positives & false negatives)  
✔️ **F1-Score** (harmonic mean of precision & recall)  
✔️ **ROC-AUC Curve** (model’s ability to distinguish fraud from legitimate transactions)  

---

## 🛠️ Technologies Used

- **Python** (NumPy, Pandas, Scikit-Learn, Matplotlib, Seaborn)
- **Machine Learning** (XGBoost, SVM, Decision Trees, Random Forest, KNN, Logistic Regression)
- **Big Data Handling** (PCA for feature extraction)
- **Data Visualization** (Matplotlib, Seaborn)
- **Jupyter Notebook** (for model experimentation)

---

## 📜 Results & Insights

✔️ **XGBoost and Random Forest achieved the highest accuracy and recall.**  
✔️ **Handling imbalanced data was crucial for improving model performance.**  
✔️ **SMOTE & ADASYN helped improve fraud detection rates.**  

---

## 📂 Project Structure


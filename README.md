# 💳 Credit Card Fraud Detection

Credit card transactions have become a cornerstone of modern society, facilitating financial exchanges across the globe. However, with the exponential growth of online and electronic payments, opportunities for fraud have also increased.  

This project applies **machine learning algorithms** to detect fraudulent credit card transactions using a **supervised learning approach**.

---

## 📊 Project Overview

The goal of this project is to **identify fraudulent transactions** from a highly imbalanced dataset.  
We use data preprocessing, visualization, and classification techniques to develop a model capable of detecting fraudulent activity.

---

## 🧠 Dataset Information

**Source:** [Kaggle - Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  

**Description:**
- Transactions made by European cardholders in **September 2013**
- Contains **284,807 transactions**, including **492 fraud cases**
- The dataset is **highly imbalanced**, with frauds representing only **0.172%** of transactions
- Features: `V1` to `V28` (PCA components), `Amount`, and `Time`
- Target variable:  
  - `0` → Non-fraudulent transaction  
  - `1` → Fraudulent transaction  

---

## ⚙️ Project Workflow

### 1. Data Processing
- Import and clean dataset  
- Standardize numerical features using `StandardScaler`  
- Split data into **train** and **test** sets  

### 2. Exploratory Data Analysis (EDA)
- Visualize class distribution  
- Plot correlations between features  
- Analyze transaction amount and time patterns  

### 3. Model Training & Evaluation
- Train models using machine learning algorithms such as:
  - **Logistic Regression**
  - **Random Forest**
  - **Decision Tree**
  - **XGBoost** *(if included)*
- Evaluate models using:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-Score**
  - **Confusion Matrix**

### 4. Handling Imbalanced Data
- Apply **under-sampling** or **SMOTE (Synthetic Minority Oversampling Technique)** to balance the dataset.

---

## 🧪 Technologies Used

| Category | Libraries / Tools |
|-----------|------------------|
| Data Manipulation | `pandas`, `numpy` |
| Visualization | `matplotlib`, `seaborn` |
| Machine Learning | `scikit-learn` |
| Evaluation Metrics | `accuracy_score`, `precision_score`, `recall_score`, `f1_score`, `confusion_matrix` |

---

## 📈 Results Summary

- Fraud cases are **successfully identified** using machine learning models.
- Due to the **class imbalance**, **recall and precision** are more reliable than accuracy.
- The **Random Forest** model provided the most balanced performance in detecting fraudulent transactions.


---

## 🧾 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/<your-username>/Credit-Card-Fraud-Detection.git
   cd Credit-Card-Fraud-Detection

# 🛡️ Credit Card Fraud Detection

This project uses machine learning classification algorithms to detect fraudulent credit card transactions. It includes data preprocessing, handling class imbalance, model training, and evaluation using performance metrics such as **precision**, **recall**, and **ROC-AUC** to ensure accurate fraud detection.

## 📂 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Pipeline](#project-pipeline)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Results & Evaluation](#results--evaluation)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## 📌 Overview

Credit card fraud is a critical issue in financial systems. Due to the **highly imbalanced nature** of fraud datasets (very few fraudulent transactions), building a reliable detection system is challenging.

This project demonstrates:
- Data preprocessing and exploration
- Handling class imbalance with techniques like SMOTE and undersampling
- Training multiple classification models
- Evaluating model performance using precision, recall, F1-score, and ROC-AUC

---

## 📊 Dataset

The dataset used is the [Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) from Kaggle, containing transactions made by European cardholders in September 2013.

- **Total Transactions**: 284,807
- **Fraudulent Transactions**: 492 (approx. 0.17%)

**Features**:
- 30 numerical input variables (V1 to V28, Time, Amount)
- Target variable: `Class` (0 = Legitimate, 1 = Fraudulent)

---

## 🔁 Project Pipeline

1. **Data Loading & Exploration**
2. **Preprocessing**
   - Feature scaling
   - Correlation analysis
3. **Handling Class Imbalance**
   - SMOTE (Synthetic Minority Over-sampling Technique)
   - Random Undersampling
4. **Model Training**
   - Logistic Regression
   - Random Forest
   - XGBoost / LightGBM (optional)
5. **Evaluation**
   - Confusion Matrix
   - Precision, Recall, F1-Score
   - ROC-AUC Curve

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Imbalanced-learn (SMOTE)
- XGBoost / LightGBM (optional)

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection

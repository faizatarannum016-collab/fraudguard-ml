# 🛡️ FraudGuard

AI-Powered Credit Card Fraud Detection System.

## 🎯 Project Objective

FraudGuard uses Machine Learning to identify potentially fraudulent credit card transactions while reducing incorrect fraud alerts.

## 🤖 Machine Learning

- Dataset: Kaggle Credit Card Fraud Detection 2026
- Model: Random Forest Classifier
- Transactions: 20,000
- Fraud cases: 339
- Fraud rate: 1.70%
- Optimized decision threshold: 25%

## 📊 Evaluation

The model is evaluated using:

- Precision
- Recall
- F1 Score
- Confusion Matrix

Accuracy is not used as the only metric because the dataset is highly imbalanced.

## 🔄 Workflow

Kaggle Dataset
↓
Data Preprocessing
↓
Feature Encoding
↓
Random Forest
↓
Fraud Probability
↓
Optimized Threshold
↓
Fraud / Safe Decision

## 💻 Technologies

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Gradio
- Google Colab

## 🚀 Application

FraudGuard provides an interactive interface where a transaction can be analyzed and assigned a fraud-risk score.

## 📁 Project Structure

FRAUDGUARD/
│
├── FRAUDGUARD_ML.ipynb
└── README.md

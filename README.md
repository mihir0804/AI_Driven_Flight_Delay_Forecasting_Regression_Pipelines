# ✈️ AI-Driven Flight Delay Forecasting

This project leverages machine learning to predict flight delays based on historical flight and scheduling data. It includes data preprocessing, feature engineering, model training and validation, class balancing, and deployment via a Gradio web app.

---

## 📂 Project Overview

Flight delays are a major challenge for airlines and passengers. By forecasting delays, airlines can improve scheduling and passenger communication.

This project demonstrates an end-to-end ML pipeline that:
- Loads and prepares flight data
- Performs exploratory data analysis (EDA)
- Engineers relevant features
- Trains and compares multiple classifiers
- Balances class distributions using SMOTE
- Validates performance with cross-validation
- Deploys an interactive prediction app with Gradio

---

## 🚀 Features

✅ Data Cleaning & Preparation  
✅ Feature Engineering (e.g., departure hour extraction, distance binning)  
✅ Label Encoding of categorical variables  
✅ Multiple ML Models:
- Random Forest
- Logistic Regression
- XGBoost
- Support Vector Machine  

✅ Model Evaluation:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC AUC

✅ Class Imbalance Handling with SMOTE  
✅ Cross-validation for robust performance estimation  
✅ Gradio Interface for interactive predictions  

---

## 📊 Dataset

The dataset includes columns such as:
- Carrier
- Departure Time
- Origin
- Destination
- Distance
- Day of the Week
- Flight Number
- Date
- Delay Status (target variable)

---

## 🧠 Model Performance

Models were evaluated via cross-validation and on a holdout test set.  
**Validated Accuracy:** ~84%  
**Validated F1 Score:** ~84%  

Random Forest achieved the best overall balance of metrics.

---

## 🛠️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/flight-delay-forecasting.git
   cd flight-delay-forecasting

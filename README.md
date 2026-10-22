# 📈 Telecom Customer Churn Prediction & Classification Pipeline

## 📌 Project Overview
This repository contains an end-to-end machine learning classification pipeline built using **Python** to predict whether a telecom customer will churn (leave the service). The project focuses heavily on handling severe class imbalance and evaluating multiple model architectures to maximize predictive accuracy.

## 🛠️ Key Methodologies & Workflow
- **Exploratory Data Analysis (EDA):** Analyzed customer behavioral patterns and feature distributions.
- **Handling Class Imbalance:** Implemented **SMOTENC** (Synthetic Minority Over-sampling Technique for Nominal and Continuous features) to balance minority class observations without distorting categorical variables.
- **Model Training & Validation:** Trained and compared multiple classifiers using **Stratified k-fold cross-validation** to ensure robust and stable results:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier

## 📊 Performance & Results
- **Best Model:** Random Forest Classifier
- **Precision:** 0.74
- **F1-Score:** 0.73
- Successfully minimized classification error rates across mixed feature spaces.

## 📂 Repository Structure
- `churn_prediction.ipynb`: Main script containing data preprocessing, SMOTENC implementation, and model training.
- `README.md`: Project documentation and overview.

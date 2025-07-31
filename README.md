# 📊 Garment Factory Productivity Prediction and Optimization

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![R](https://img.shields.io/badge/R-Statistics-blue)
![ML](https://img.shields.io/badge/ML-scikit--learn-yellow)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📚 Overview

This project investigates the progression of Alzheimer’s disease using clinical and demographic data. By leveraging machine learning models, the project aims to predict disease severity levels and contribute to earlier, more personalized medical interventions.
Our analysis includes exploratory data analysis (EDA), feature selection, and classification modeling to distinguish between different stages of cognitive impairment.

---

## 🎯 Objectives

Explore patient data to identify key features associated with Alzheimer’s severity
Preprocess and balance the dataset for robust model training
Build predictive models to classify patients based on Clinical Dementia Rating (CDR)
Evaluate model performance using accuracy, precision, recall, and F1-score
Interpret feature importance and support clinical insight into disease progression

## 📈 Results Summary

| Model                | Train Accuracy | Test Accuracy | Precision | Recall | F1 Score |
|---------------------|----------------|---------------|-----------|--------|----------|
| **AdaBoost**         | 0.946          | **0.947**     | 0.948     | 0.947  | **0.947** |
| XGBoost             | 0.930          | 0.926         | 0.930     | 0.926  | 0.927     |
| Random Forest       | 0.913          | 0.912         | 0.910     | 0.903  | 0.909     |
| SVM                 | 0.835          | 0.812         | 0.810     | 0.812  | 0.810     |
| Logistic Regression | 0.833          | 0.805         | 0.803     | 0.805  | 0.803     |

## 💡 Conclusion & Recommendations
AdaBoost proved to be the most effective model for predicting Alzheimer’s diagnosis severity, demonstrating:
Highest test accuracy (94.7%)
Strong balance between precision and recall
Best F1 score (94.7%), indicating robust generalization
XGBoost and Random Forest also performed well but showed slightly lower accuracy and generalization ability compared to AdaBoost.
SVM and Logistic Regression underperformed in comparison, suggesting they are less suitable for this specific dataset.

Recommendations:
Adopt AdaBoost as the primary diagnostic model in production-level screening systems for Alzheimer’s severity risk.
Regularly retrain the model with new patient data to ensure performance consistency and adapt to evolving patterns.
Explore integrating neuroimaging features or longitudinal health data to further boost predictive accuracy.
Deploy the model in clinical decision support tools to assist practitioners with early diagnosis and resource prioritization.

## Contributors
- Meedum Keerthisiri
- Samudika Wanasinghe
- Pasindu Gamage

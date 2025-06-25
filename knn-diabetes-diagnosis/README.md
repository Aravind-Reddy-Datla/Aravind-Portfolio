# 🔬 Diabetes Diagnosis Prediction Using KNN

## 📌 Problem Statement
Predict whether a patient is diabetic based on clinical features using machine learning.

## 🎯 Objective
Build a K-Nearest Neighbors (KNN) model to achieve high classification accuracy and interpret feature importance.

## 🛠️ Tools & Techniques
- Python, Pandas, Scikit-learn, Jupyter Notebook
- StandardScaler, ANOVA Feature Selection
- GridSearchCV for hyperparameter tuning

## 📊 Process Overview
1. Cleaned and preprocessed patient data
2. Scaled features for distance-based modeling
3. Used ANOVA to select top predictors
4. Tuned `n_neighbors`, `weights`, and `metric` via cross-validation
5. Evaluated using accuracy, confusion matrix, and ROC-AUC

## ✅ Outcome
- Final Accuracy: **91.7%**
- KNN model outperformed baseline and showed strong generalization
- Reduced dimensionality without loss in predictive power

## 📈 Future Work
- Compare with logistic regression and random forest
- Build a Streamlit app to make the model interactive

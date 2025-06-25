# 🔬 Diabetes Diagnosis Prediction Using KNN

## 🧠 About the Project
This portfolio project demonstrates my personal implementation of the **K-Nearest Neighbors (KNN)** algorithm to solve a real-world classification task—predicting diabetes presence in patients using clinical features. The aim is to enhance diagnostic accuracy using machine learning fundamentals while strengthening my end-to-end modeling workflow.

## 📌 Problem Statement
Given a dataset of patient records, can we accurately classify whether a person is diabetic based on physiological data like glucose levels, BMI, and blood pressure?

## 🎯 Objective
To build a robust KNN classification model with optimal hyperparameters, evaluate its performance against baselines, and interpret feature significance.

## 🛠️ Tools & Techniques Used
- **Language & Libraries**: Python, NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
- **Feature Engineering**: Label Encoding, ANOVA F-test for feature selection
- **Modeling**: KNN Classifier, `train_test_split`, `GridSearchCV`

## 📊 Workflow Summary
1. Cleaned and standardized patient health data
2. Performed feature selection using ANOVA (f_classif)
3. Applied `StandardScaler` for consistent distance metrics
4. Trained baseline and tuned KNN models using `GridSearchCV`
5. Compared performance using cross-validation and visualizations

## ✅ Results
- Achieved **91.7% accuracy** with optimized hyperparameters
- Tuned parameters included: `n_neighbors`, `weights`, `metric`
- High generalization validated through cross-validation

## 📈 Next Steps
- Compare results with Logistic Regression and Random Forest
- Create an interactive **Streamlit web app** for real-time predictions

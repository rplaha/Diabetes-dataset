# Healthcare Dataset Project: Predicting Diabetes

## Objective:
The goal of this project is to predict diabetes status based on various medical and demographic factors. The dataset includes test results like Urea, HbA1c, Cholesterol, and patient details such as age and gender. The target variable is the **CLASS** column, representing diabetes diagnosis (Y for diabetic, N for non-diabetic).

## Dataset Overview:
- **Gender:** Categorical (M for male, F for female).
- **Age:** Continuous variable representing patient age.
- **Medical Tests:** Includes Urea, Cr, HbA1c, Chol, TG, HDL, LDL, and VLDL.
- **BMI:** Body Mass Index, a critical predictor for diabetes.
- **CLASS:** Target variable (Y/N) for diabetes status.

## Exploratory Data Analysis (EDA):
- Handled missing values, duplicates, and standardized data types.
- Correlation analysis revealed **Cr** and **Urea** as highly correlated features.
- Patients aged 50-55 are at higher risk, with more female patients reported.

## Machine Learning Models:
To solve this binary classification problem, the following models were applied:
- Logistic Regression (LR)
- k-Nearest Neighbors (KNN)
- Naive Bayes (NB)
- Support Vector Classifier (SVC)
- Random Forest Classifier (RFC)
- Decision Tree Regressor (DTR)
- XGBoost (XGB)

Train-test split and cross-validation were used for evaluation, with metrics like accuracy, precision, recall, and F1-score.

## Results:
The **XGBoost (XGB)** model achieved the highest accuracy and was selected as the best model for predicting diabetes.

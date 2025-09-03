# Customer-Churn-Prediction-Scikit-learn-
A compact, production-style ML project that predicts customer churn using Python and scikit-learn.   It includes clean preprocessing, model training with cross-validation, metrics, and an inference script.
# Customer Churn Prediction

A compact, production-style ML project that predicts customer churn using Python and scikit-learn.  
It includes clean preprocessing, model training with cross-validation, metrics, and an inference script.

## ✨ Highlights
- One-hot + numeric scaling pipeline (ColumnTransformer)
- Logistic Regression and Random Forest with GridSearchCV
- Metrics: ROC-AUC, accuracy, F1, confusion matrix
- Reproducible, CLI-driven scripts (`src/train.py`, `src/infer.py`)

## 📦 Data
CSV at: `data/telecom_churn.csv`.

**Required columns:**  
`Churn` (Yes/No), `gender`, `SeniorCitizen`, `Partner`, `Dependents`,  
`tenure`, `PhoneService`, `MultipleLines`, `InternetService`, `OnlineSecurity`,  
`OnlineBackup`, `DeviceProtection`, `TechSupport`, `StreamingTV`, `StreamingMovies`,  
`Contract`, `PaperlessBilling`, `PaymentMethod`, `MonthlyCharges`, `TotalCharges`



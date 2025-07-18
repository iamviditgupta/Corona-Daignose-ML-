# Corona-Daignose-ML-
Utilized Python libraries including pandas, num Py, seaborn, matplotlib, and scikit-learn to develop a predictive model for COVID-19 testing, focusing on data processing, analysis, and visualization.

Predicting COVID-19 test outcomes using symptom data and demographic features.
This project uses machine learning models to predict the likelihood of a positive COVID-19 diagnosis based on symptoms (like fever, cough, shortness of breath), patient demographics (age, gender), and contact history. The dataset, sourced from a real-world government health database (Israel, via Kaggle), contains over 270,000 patient records collected during the initial wave of the pandemic.

🧠 Key Highlights:
Applied multiple classifiers: Logistic Regression, Random Forest, XGBoost, KNN, SVM

Best performance achieved with XGBoost, with an AUC of 0.83 and F1-score ~0.64

Chi-square statistical analysis was conducted to validate feature importance

Preprocessing included case normalization, mode imputation, and label encoding

ROC-AUC curve used to evaluate model sensitivity and classification thresholds

Final models help identify likely positive cases for early triage and response in crisis settings



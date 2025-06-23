# Loan Default Prediction 🚨💰

This project aims to build a machine learning model to **predict loan defaults** using the **Lending Club Loan Dataset**. By analyzing financial and personal information of borrowers, the model helps lenders identify **high-risk applicants**, reducing financial losses due to defaults.

---

## 🔍 Objective

To develop a classification model that predicts whether a loan applicant will default, enabling financial institutions to make informed lending decisions.

---

## 📁 Dataset

- **Source:** [Lending Club Loan Dataset](https://www.kaggle.com/datasets/wendykan/lending-club-loan-data)
- **Target Variable:** `loan_status` (converted to binary: 1 = Default, 0 = No Default)

---

## 🛠️ Features Used

- Loan amount (`loan_amnt`)
- Interest rate (`int_rate`)
- Annual income (`annual_inc`)
- Debt-to-income ratio (`dti`)
- Delinquencies (`delinq_2yrs`)
- Employment length (`emp_length`)
- Home ownership
- Loan purpose
- And more...

---

## 🧪 Steps Involved

1. **Data Preprocessing**
   - Handled missing values
   - Converted categorical features using one-hot encoding
   - Binary label transformation (`loan_status`)
   - Addressed class imbalance using **SMOTE**
   - Scaled features using **StandardScaler**

2. **Model Training**
   - **LightGBM** Classifier
   - **SVM** Classifier

3. **Model Evaluation**
   - Precision, Recall, F1-Score
   - Classification Report
   - Feature Importance for interpretability

4. **Outcome**
   - A trained ML model that flags potential defaulters for better credit risk management.

---

## 📈 Results

- Achieved high **F1 Score** and **Recall** using LightGBM
- Identified top features contributing to default risk
- Provided recommendations for lending policy improvements

---

## 📊 Sample Visuals

- 📌 Feature Importance (LightGBM)
- 📉 Confusion Matrix
- 📈 Performance metrics (Precision, Recall, F1)


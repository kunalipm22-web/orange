# 🏦 Loan Approval Prediction using Orange Data Mining

### Machine Learning • Logistic Regression • Classification Analysis • Banking Analytics

---

## 📌 Project Overview

This project uses **Orange Data Mining** to predict whether a loan application will be approved or rejected based on customer information.

The objective is to build a classification model using **Logistic Regression** and evaluate its performance using cross-validation techniques.

This project demonstrates the application of machine learning in banking and financial decision-making.

---

## 🎯 Objectives

- Predict loan approval status
- Analyze customer creditworthiness
- Apply Logistic Regression for classification
- Evaluate model performance
- Support banking decision-making
- Demonstrate machine learning using Orange Data Mining

---

## 📊 Dataset Description

The dataset contains loan applicant information.

### Input Features (Independent Variables)

| Feature | Description |
|----------|------------|
| Gender | Male or Female |
| Age | Customer Age |
| Married | Marital Status |
| Dependents | Number of Dependents |
| Education | Graduate / Not Graduate |
| Self_Employed | Employment Status |
| Income | Customer Income |
| Coapplicant_Income | Co-applicant Income |
| Loan_Amount | Requested Loan Amount |
| Loan_Term | Loan Duration |
| Credit_History | Good/Poor Credit History |
| Property_Area | Urban / Rural / Semiurban |
| Employment_Years | Work Experience |

### Target Variable (Dependent Variable)

| Variable | Meaning |
|-----------|---------|
| Loan_Approved = 1 | Loan Approved |
| Loan_Approved = 0 | Loan Rejected |

---

## 🏗 Orange Workflow

The machine learning workflow was developed using Orange Data Mining.

### Steps Performed

### Step 1 — Load Dataset
- File Widget
- Import CSV dataset

### Step 2 — Select Target Variable
- Select Columns Widget
- Set **Loan_Approved** as Target Variable

### Step 3 — Apply Logistic Regression
- Logistic Regression Widget
- Train classification model

### Step 4 — Model Evaluation
- Test & Score Widget
- Perform Cross Validation

### Step 5 — Performance Analysis
- Accuracy
- AUC
- Precision
- Recall
- F1 Score
- MCC

---

# 📸 Project Screenshots

## 🔄 Orange Workflow

The workflow consists of:

- File Widget
- Select Columns
- Logistic Regression
- Test & Score

This workflow trains and evaluates a loan approval prediction model.

![Orange Workflow](./orange-workflow.png)

---

## 📈 Model Evaluation Results

The model was evaluated using Cross Validation in Orange.

Metrics analyzed:

- AUC
- Classification Accuracy
- F1 Score
- Precision
- Recall
- MCC

![Model Results](./orange-test-score-results.png)

---

## 🤖 Model Used

### Logistic Regression

Logistic Regression is a supervised machine learning algorithm used for binary classification problems.

In this project it predicts:

- Loan Approved
- Loan Rejected

based on customer financial information.

---

## 📊 Model Results

| Metric | Value |
|----------|---------|
| AUC | 0.52 |
| Accuracy | 65% |
| F1 Score | 0.58 |
| Precision | 0.62 |
| Recall | 0.65 |
| MCC | 0.14 |

---

## 🔍 Interpretation

- The model provides moderate predictive performance.
- Credit history and income significantly influence loan approval decisions.
- Logistic Regression offers an interpretable and efficient classification approach.
- The model can support preliminary loan screening.

---

## 💼 Business Understanding

Banks can use this model to:

- Reduce risky lending decisions
- Improve loan approval efficiency
- Support credit risk assessment
- Automate initial customer screening
- Improve operational productivity

---

## ⚠ Limitations

- Accuracy is moderate
- Dataset size is limited
- Logistic Regression may not capture complex patterns
- Additional features may improve performance

---

## 🛠 Tools & Technologies

| Technology | Purpose |
|------------|----------|
| Orange Data Mining | Machine Learning Platform |
| Logistic Regression | Classification Model |
| CSV Dataset | Data Source |
| Cross Validation | Model Evaluation |
| Banking Analytics | Business Application |

---

## 📂 Repository Structure

```text
loan-approval-prediction/
│
├── README.md
├── loan_approval_dataset_100_rows.csv
├── orange-workflow.png
└── orange-test-score-results.png
```

---

## 🚀 How to Run

1. Open Orange Data Mining
2. Load the dataset using File Widget
3. Add Select Columns Widget
4. Set Loan_Approved as Target
5. Connect Logistic Regression
6. Connect Test & Score
7. Run Cross Validation
8. Analyze model performance

---

## 📈 Future Improvements

- Random Forest Classifier
- Decision Tree Analysis
- XGBoost Model
- Larger Dataset
- Hyperparameter Tuning
- Feature Engineering
- Banking Risk Dashboard

---

## 👨‍💻 Developed By

**Kunal Taneja**

MBA (Applied Finance)

Machine Learning • Banking Analytics • Risk Management • Data Analytics

⭐ If you found this project useful, consider giving it a star.

# 🏦 Loan Approval Prediction using Orange Data Mining

### Machine Learning | Logistic Regression | Banking Analytics

---

## 📌 Project Overview

This project predicts whether a loan application will be approved or rejected using Logistic Regression in Orange Data Mining.

The model analyzes customer demographic and financial information and classifies applicants into approved or rejected categories.

---

## 🎯 Objectives

- Predict loan approval status
- Apply Logistic Regression
- Evaluate model performance
- Support banking decision-making
- Demonstrate machine learning concepts

---

## 📊 Dataset Description

The dataset contains customer loan application information.

### Input Features

- Gender
- Age
- Married
- Dependents
- Education
- Self Employed
- Income
- Coapplicant Income
- Loan Amount
- Loan Term
- Credit History
- Property Area
- Employment Years

### Target Variable

**Loan_Approved**

- 1 = Approved
- 0 = Rejected

---

## 🏗 Workflow in Orange

### Step 1: Load Dataset
Import the CSV dataset using the File widget.

### Step 2: Select Target Variable
Use Select Columns and move Loan_Approved to Target.

### Step 3: Train Model
Apply Logistic Regression.

### Step 4: Evaluate Model
Use Test & Score widget with Cross Validation.

### Step 5: Analyze Results
Review Accuracy, AUC, Precision, Recall, F1 Score, and MCC.

---

# 📸 Project Screenshots

## 🔄 Orange Workflow

The workflow loads the dataset, selects the target variable, trains a Logistic Regression model, and evaluates performance using Test & Score.

<img src="assets/orange-workflow.png" width="900">

---

## 📈 Model Evaluation Results

Performance metrics generated using Orange Test & Score widget.

<img src="assets/orange-test-score-results.png" width="900">

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
- Credit history significantly influences loan approval.
- Logistic Regression offers a simple and interpretable solution.
- The model can support preliminary loan screening.

---

## 💼 Business Understanding

Banks can use this model to:

- Reduce risky lending decisions
- Improve approval efficiency
- Support credit risk assessment
- Automate customer screening

---

## ⚠ Limitations

- Moderate accuracy
- Limited dataset size
- May not capture complex relationships

---

## 🛠 Tools Used

| Tool | Purpose |
|--------|----------|
| Orange Data Mining | Machine Learning |
| Logistic Regression | Classification |
| CSV Dataset | Data Source |
| Test & Score | Evaluation |

---

## 📂 Repository Structure

```text
Loan-Approval-Prediction/
│
├── README.md
├── loan_approval_dataset_100_rows.csv
│
└── assets/
    ├── orange-workflow.png
    └── orange-test-score-results.png
```

---

## 🚀 How to Run

1. Open Orange Data Mining
2. Import dataset using File widget
3. Add Select Columns widget
4. Set Loan_Approved as Target
5. Add Logistic Regression
6. Add Test & Score
7. Run Cross Validation
8. Analyze results

---

## 👨‍💻 Developed By

**Kunal Taneja**

MBA (Applied Finance)

Machine Learning • Banking Analytics • Risk Analytics

⭐ If you found this project useful, consider giving it a star.

# 🏦 Loan Approval Prediction using Orange Data Mining

### Machine Learning • Logistic Regression • Banking Analytics • Classification Modeling

---

## 📌 Project Overview

This project predicts whether a loan application will be approved or rejected using **Logistic Regression** in **Orange Data Mining**.

The model analyzes customer demographic and financial information and classifies applicants into approved or rejected categories. The project demonstrates how machine learning can support banking and credit risk decision-making.

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
| Credit_History | Credit Record |
| Property_Area | Urban / Semiurban / Rural |
| Employment_Years | Work Experience |

### Target Variable (Dependent Variable)

| Variable | Meaning |
|-----------|---------|
| Loan_Approved = 1 | Loan Approved |
| Loan_Approved = 0 | Loan Rejected |

---

## 🏗 Orange Workflow

### Step 1 — Load Dataset
Import the CSV dataset using the File widget.

### Step 2 — Select Target Variable
Use Select Columns and move Loan_Approved to the Target section.

### Step 3 — Train Model
Apply Logistic Regression.

### Step 4 — Evaluate Model
Connect Test & Score widget.

### Step 5 — Cross Validation
Perform model validation and generate evaluation metrics.

---

# 📸 Project Screenshots

## 🔄 Orange Workflow

The workflow loads the dataset, selects the target variable, trains a Logistic Regression model, and evaluates performance using Test & Score.

<img src="https://raw.githubusercontent.com/kunalipm22-web/orange/main/orange-workflow.png.png" width="900">

---

## 📈 Model Evaluation Results

Performance metrics generated using Orange Test & Score widget.

<img src="https://raw.githubusercontent.com/kunalipm22-web/orange/main/orange-test-score-results.png.png" width="900">

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
- Credit history significantly influences loan approval decisions.
- Logistic Regression provides an interpretable classification approach.
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

- Moderate accuracy
- Limited dataset size
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
orange/
│
├── README.md
├── loan_approval_dataset_100_rows.csv
├── orange-workflow.png.png
└── orange-test-score-results.png.png
```

---

## 🚀 How to Run

1. Open Orange Data Mining
2. Load the dataset using File widget
3. Add Select Columns widget
4. Set Loan_Approved as Target
5. Add Logistic Regression
6. Add Test & Score
7. Run Cross Validation
8. Analyze model performance

---

## 📈 Future Improvements

- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Model
- Larger Dataset
- Feature Engineering
- Hyperparameter Tuning
- Banking Risk Dashboard

---

## 👨‍💻 Developed By

**Kunal Taneja**

MBA (Applied Finance)

Machine Learning • Banking Analytics • Risk Analytics • Data Science

⭐ If you found this project useful, consider giving it a star.

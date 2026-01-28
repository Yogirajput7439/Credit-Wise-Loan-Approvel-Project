# Credit Wise Loan Approval System

A machine learning based loan approval system that predicts whether a loan
should be approved or rejected based on an applicant’s creditworthiness
and financial details.

---

## Problem Statement

Loan approval is a critical process for banks and financial institutions.
Manual evaluation of loan applications is time-consuming and may lead to
human bias or errors.

The **Credit Wise Loan Approval System** automates this process using
machine learning to make accurate, fast, and data-driven loan decisions.

---

## Features

- Predicts loan approval based on credit and financial parameters
- Performs data cleaning and preprocessing
- Uses machine learning classification algorithms
- Evaluates model performance using multiple metrics
- Reduces risk and improves decision accuracy

---

## Tech Stack & Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Dataset Information

The dataset contains financial and personal details of loan applicants:

- Applicant Income
- Co-applicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Employment Status
- Property Area

** Target Variable:**  
- `Loan_Status` (Approved / Not Approved)

---

## Machine Learning Models Used

- Logistic Regression
- Label Encoder
- One Hot Encoder
- StandardScaler
- KNeighborsClassifier
- GaussianNB
- 

Among these, **Gaussian Naive Bayes** provided the best overall performance.

---

## 📈 Model Evaluation

The models were evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

These metrics help in understanding both prediction quality and class balance.

---

## ⚙️ Project Workflow

1. Data Collection
2. Data Cleaning & Handling Missing Values
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Loan Approval Prediction

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yogirajput7439/Credit-Wise-Loan-Approvel-Project

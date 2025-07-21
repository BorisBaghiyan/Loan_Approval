# 🏦 Loan Approval — Machine Learning Project

This project focuses on predicting loan approval decisions based on applicant information such as income, credit history, employment status, and more.  
The goal is to assist banks or financial institutions in making smarter, faster, and data-driven loan approval decisions using machine learning.

---

## 📌 Project Overview

The dataset includes features related to:
- Personal and financial information of applicants  
- Loan details (amount, term, credit history, etc.)  
- Target column: Loan_Status (approved or not)

The project explores data preprocessing, model training, and evaluation of different classification algorithms to build a reliable loan approval predictor.

---

## 📁 Repository Structure

- Loan_approval.ipynb — main notebook containing the full pipeline: data cleaning, encoding, model training, and evaluation  
- train.csv — dataset used for training  
- submission.csv — predictions ready for submission (if used in a competition context)  
- README.md — project description

---

## 🚀 Installation

1. Clone the repository:
```
git clone https://github.com/BorisBaghiyan/Loan_Approval.git
```
2. Navigate to the project directory:
```
cd Loan_Approval
```
3.(Optional) Create and activate a virtual environment
```
python -m venv
venv\Scripts\activate
```
4. Install the required packages:
```
pip install requirements.txt
```

## 🧪 How to Use
1.Open Loan_approval.ipynb using Jupyter Notebook or Google Colab

2.Run the cells step-by-step to explore, preprocess, and train models

3.Check the final evaluation and prediction results

4.(Optional) Export predictions to submission.csv if needed

## 📊 Models & Approach
The notebook may include models such as:

.Logistic Regression

.Decision Trees

.Random Forest

.XGBoost / LightGBM (optional)

Evaluation metrics include accuracy, confusion matrix, and cross-validation.

# CreditWise Loan System

## Project Overview
CreditWise Loan System explores a Machine Learning workflow for predicting whether a loan application is approved or rejected using applicant, financial, employment, and credit-related attributes.

The project notebook covers data loading, missing-value handling, exploratory data analysis (EDA), feature encoding, correlation analysis, train-test splitting, feature scaling, and classification models.

## Dataset
The dataset file is `loan_approval_data.csv`. It contains 1,000 rows and 20 columns, including:
- Applicant income and co-applicant income
- Employment status, age, marital status, and dependents
- Credit score, existing loans, and debt-to-income ratio
- Savings, collateral value, loan amount, and loan term
- Loan purpose, property area, education level, gender, and employer category
- `Loan_Approved` — target label (`Yes` / `No` in the supplied CSV)

## Repository Contents
```text
CreditWise-Loan-System/
├── Credit_wise.ipynb
├── loan_approval_data.csv
├── requirements.txt
├── .gitignore
└── README.md
```

## Tools and Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Getting Started
1. Clone or download this repository.
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `Credit_wise.ipynb` in Jupyter Notebook.
4. Keep `loan_approval_data.csv` in the same directory as the notebook.
5. Run the notebook cells in order.

Start Jupyter with:
```bash
jupyter notebook
```

## Modeling Notes
The notebook includes Logistic Regression, K-Nearest Neighbors (KNN), and Gaussian Naive Bayes model sections. Review the notebook and run all cells to verify outputs and evaluation results in your environment before reporting model performance.

## Responsible Use
Loan approval predictions can affect access to financial services. Treat model outputs as decision-support only, evaluate performance and fairness across applicant groups, and require qualified human review before making real lending decisions. Do not publish confidential or personally identifiable customer information.

## Project Status
Work in progress.

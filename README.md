# lgd-score-prediction-in-ifrs-9

# IFRS LGD Prediction Model

## Overview
This repository contains a Linear Regression model for predicting Loss Given Default (LGD) according to International Financial Reporting Standards (IFRS). The model utilizes bank data with various features to estimate the LGD.

## Dataset
The dataset used for training and testing the model includes the following columns:
- **Exposure Amount ($)**: The amount of exposure in dollars.
- **LGD ($)**: Loss Given Default in dollars.
- **Credit Score**: The credit score of the borrower.
- **Loan Term (Months)**: The term of the loan in months.
- **Interest Rate (%)**: The interest rate on the loan.
- **Income ($)**: Income of the borrower.
- **Loan to Value Ratio (%)**: Ratio of the loan amount to the appraised value of the property.
- **Debt to Income Ratio (%)**: Ratio of the borrower's total debt to their total income.
- **Employment History (Years)**: Number of years of employment history.
- **Previous Defaults**: Number of previous defaults.
- **Home Ownership**: Whether the borrower owns a home.
- **Loan Purpose**: Purpose of the loan.
- **Loan Type**: Type of the loan.
- **Region**: Region where the loan is originated.

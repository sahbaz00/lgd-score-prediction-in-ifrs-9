
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

## Model
The model is built using Linear Regression, a simple yet effective method for predicting continuous outcomes. It is trained on the provided dataset to predict the LGD based on the input features.

## Usage
To use the model:
1. Clone this repository to your local machine.
2. Install the necessary dependencies specified in `requirements.txt`.
3. Run the provided script to train the model and make predictions.
4. Customize the model or add more features as needed for your specific use case.

## Repository Structure
- `data/`: Contains the dataset used for training and testing.
- `model/`: Includes the Python script for training the model.
- `README.md`: This file providing an overview of the project.

## Contributors
- [Shahbaz Khalilli](https://github.com/sahbaz00) - Role

Feel free to contribute to this project by forking the repository and submitting pull requests with improvements or additional features.
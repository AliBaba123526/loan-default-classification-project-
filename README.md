# Loan Default Prediction

## Project Overview
This project aims to predict whether a loan applicant is likely to default on a loan. The goal is to support better loan approval decisions using data science and machine learning.

## Business Problem
Banks and lenders face financial risk when customers fail to repay loans. A predictive model can help identify high-risk applicants before approval.

## Decision Maker
The main decision maker is the loan approval team or automated loan approval system.

## Business Decision
The business decision is to assess the risk of loan default before approving a loan.

## Possible Actions
Based on the predicted risk, the lender may:
- approve the loan
- reject the loan
- offer a lower loan amount
- adjust loan terms to balance profitability and risk exposure

## Target Variable
The target variable is loan default:
- 1 = default
- 0 = no default

In this project, default means missing payments for 90 days or more.

## Why This Matters
A False Negative is especially costly because it means the model predicts a customer will not default, but they actually do, causing financial loss to the lender.

## Planned Workflow
1. Define the business problem
2. Load and inspect the data
3. Perform purposeful EDA
4. Clean and preprocess the data
5. Build classification models
6. Evaluate model performance
7. Tune decision threshold if needed
8. Translate results into business recommendations

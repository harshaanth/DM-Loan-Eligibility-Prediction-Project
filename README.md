# Loan-Eligibility-Prediction-Project

## Overview
This project aims to automate the loan eligibility determination process for Dream Housing Finance company. By analyzing customer details such as income, credit history, and property area, a logistic regression model is employed to predict whether a customer is likely to get their loan approved.

## Business Objective
The primary business objective is to identify which customer segments are more likely to have their loans approved. This allows the company to specifically target these customers, improving efficiency and customer satisfaction.

## Project Details
- **Dataset**: Contains customer information such as gender, marital status, education, number of dependents, income, loan amount, and credit history.
- **Model**: Logistic regression was used to predict loan eligibility (`Loan_Status`). Significant variables include `Credit_History` and `Property_Area`.
- **Performance**: The model was evaluated using metrics like AUC, recall, specificity, and accuracy. A cutoff probability of 0.5 was chosen to balance recall and specificity.
- **Example**: Given an applicant's details, the model can predict the likelihood of loan approval.

## Files Included
- **loan-train_HK.xlsx**: The Excel file containing the dataset and logistic regression model.
- **Project_Report.pdf**: Detailed project report with analysis, charts, and model evaluation.
- **README.md**: This file, providing an overview of the project and instructions.

## Conclusion
The logistic regression model developed in this project offers valuable insights into the factors that influence loan approval. By leveraging this model, Dream Housing Finance can better target eligible customers, thereby streamlining their loan approval process.

Specifically, the model reveals that customers with a credit history and those residing in semi-urban property areas are more likely to have their loan applications approved. These insights can guide the company's efforts in identifying and focusing on the most promising customer segments.

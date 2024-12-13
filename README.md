# Credit-risk-classification
Module 20 Homework
The purpose of this analysis is to evaluate the performance of a logistic regression model in predicting the likelihood of a loan being "healthy" (0) or "high-risk" (1). This classification task is critical for the company to manage financial risks effectively and make informed decisions about lending.

The dataset contains financial information about loans, including:

loan_size: The size of the loan.
interest_rate: The loan’s interest rate.
borrower_income: The borrower’s annual income.
debt_to_income: The ratio of total debt to income.
num_of_accounts: The number of financial accounts the borrower has.
derogatory_marks: The number of negative credit marks on the borrower’s report.
total_debt: The total amount of debt the borrower has.

The target variable, loan_status, indicates whether a loan is healthy (0) or high-risk (1). This shows an imbalanced dataset, with most loans classified as healthy.


The data was separated into features (X) and labels (y). The dataset was split into training and testing sets using an 80/20 split.A logistic regression model (LogisticRegression with random_state=1) was used.

The model's performance was evaluated using accuracy, precision, recall, and F1-score.

Accuracy: 
99% (The model correctly classifies 99% of loans.)
Precision:
Healthy Loans (0): 1.00
High-Risk Loans (1): 0.85
Recall:
Healthy Loans (0): 0.99
High-Risk Loans (1): 0.94

The logistic regression model demonstrates strong performance across all metrics. It is particularly effective at classifying healthy loans (0), achieving perfect precision (1.00) and near-perfect recall (0.99). For high-risk loans (1), the model performs slightly less well, with a precision of 0.85 and recall of 0.94. These results indicate that the model is more likely to misclassify healthy loans as high-risk than vice versa. This model is recommended for use by the company. Its high recall for high-risk loans ensures that most high-risk cases are identified, minimizing financial losses.
 

I would like to acknowledge the resources and tools that supported me in completing this assignment: ChatGPT, Xpert Learning, and Stack Overflow.

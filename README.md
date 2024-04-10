# Telecom Churn Group Case Study

## Problem Statement
Customers in the telecom sector have the ability to actively move between different operators and select from a variety of service providers. The annual churn rate in the telecommunications sector is between 15 and 25 percent on average in this fiercely competitive market. Customer retention has surpassed customer acquisition in importance since it is now five to ten times more expensive to keep an existing customer than to acquire a new one. Retaining highly profitable clients is the top priority for many established operators.

Telecom firms need to identify which customers are most likely to leave in order to minimize customer attrition. In this assignment, you will examine customer-level df from a top telecom company, develop predictive models to pinpoint high-risk clients, and pinpoint the primary churn indicators.

### Consumer actions during a churn:
- **The "good" phase:** During this time, the client is satisfied with the assistance and acts normally.
- **The "action" phase:** This is when the customer's experience starts to decline. For example, they receive an alluring offer from a rival, are subjected to unfair charges, are dissatisfied with the caliber of the service, etc. Since remedial action can be performed at this time, it is imperative to identify high-churn-risk clients during this phase.
- **The "churn" phase:** In this phase, the customer is said to have churned.

### Goal
The primary objective is to build machine learning models to forecast clients who will leave based on the features made available for their use. The purpose of the model is to forecast the likelihood of a high-value client leaving in the near future (also known as the churn phase). Knowing this allows the business to take appropriate action, like offering exclusive programs or low-cost recharges.

### Methods
If performing PCA for dimensionality reduction aids in a commensurate improvement in the ensuing accuracy levels as well, we will use it to forecast clients who are likely to leave. Nevertheless, as PCA is unable to assist in the interpretation of the crucial churn factors, we will construct two models to handle goals 1) and 2) independently.

### Important Assumption
Given that the training dataset only includes three months and the issue description from Kaggle mentions four months, we infer that September, the month of the churn phase, has already been deleted from the dataset. As a result, we do not eliminate any columns from our analysis based on the churn phase.

## Steps
1. Data Interpretation
2. Data Purification (Error-prone df imputation)
3. EDA (Heatmaps -> Bivariate -> Univariate)
4. PCA Feature Selectring
5. Feature Selection (PCA)
6. Model Development with PCA (To predict churn) i.e. Logistic Regression -> Decision Tree -> Random Forest -> Gradient Boosting -> XGBoost -> CatBoost -> ...st..SVM
7. Model Evaluation (Sensitivity, Precision, Accuracy, AOC)
8. Two Final Models (two different approaches)
9. Model Development without PCA (To identify important features)


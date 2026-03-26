
# Model Risk Validation (Bernard Malhame)

Model validation using SR 11-7 outcomes analysis


**Objective**

Develop and evaluate a probability of default (PD) model using the "Give Me Some Credit" dataset (available on Kaggle for training purposes), and assess model behavior through interpretability analysis and stress testing.

**Dataset description**

The "Give Me Some Credit" dataset contains consumer credit information (150,000 rows/observations) used to predict whether a borrower will experience serious delinquency within two years (SeriousDlqin2yrs).

It includes features (10 predictor variables/columns in total) such as payment history, credit utilization, debt ratio, income, and age, which are key drivers of default risk in consumer lending.

**Approach**

- Logistic regression model for PD estimation

- Train/test split with evaluation via AUC, precision/recall

- Interpretability using SHAP (global and local explanations)

- Stress testing via shocks to key drivers (delinquency, utilization, income, debt ratio)

- Ranking stability assessed using Spearman correlation

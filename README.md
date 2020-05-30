# Detecting Credit Card Fraud: Project Overview

- Created a statistical report which proposes a machine learning model that classifies credit card transactions as fraud/genuine to help credit card companies detect fraudulent credit card activities
- Accounted for highly imbalanced data in response (only 0.17 % of total transactions in data are fraudulent) by conducting subsampling using ROSE with `trainControl` function from `caret` package
- Optimized GBM, boosted logistic regression, and neural networks using 5-fold cross validation with `trainControl` function from `caret` package

***

## Code used

**R version 3.6.1**


## Data


The [Credit Card Fraud Dataset](https://stat432.org/data/creditcard.csv.gz) was accessed via Kaggle. It contains information regarding credit card users' transaction over the span of two days in September, 2013. Most of the predictor information have been transformed with PCA due to confidentiality. Information that remains interpretable includes `Time`, `Amount`, and `Class`.

- `Time`: time elapsed (in seconds) between this transaction and the first transaction 
- `Amount`: transaction amount
- `Class`: binary variable with values `fraud` and `genuine`



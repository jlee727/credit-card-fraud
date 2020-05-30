# Detecting Credit Card Fraud: Project Overview

- Created a statistical report which proposes a machine learning model that classifies credit card transactions as fraud/genuine to help credit card companies detect fraudulent credit card activities
- Accounted for highly imbalanced data in response (only 0.17 % of total transactions in data are fraudulent) by conducting subsampling using ROSE with `trainControl` function from `caret` package
- Optimized GBM, boosted logistic regression, and neural networks using 5-fold cross validation with `trainControl` function from `caret` package

***

## Code used

**R version 3.6.1**


## Data

[Credit card fraud dataset](https://stat432.org/data/creditcard.csv.gz)


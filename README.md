# Predicting Commercial Bank Customer Retention (Churn) Rate

## Project Name

Predicting Commercial Bank Customer Retention (Churn) Rate

## Description

This project applies machine learning techniques to predict whether or not customers of a commercial bank will stay with the bank (continue with their products and services). As we enter a data-driven era, banks need a better understanding of customer demands as they expanding their business models. Specifically, banks are interested in learning about customer's churn rate and the change of their financial interests. The purpose of predicting customer's retention probability is to accommodate customer demands and to achieve precision marketing in order to retain revenues.

This project has two affiliations: 

1. It is the final project of the APSTA-GE 2401：Statistical Consulting Seminar course at New York University.

2. It is the team project of an active competition on Data Castle: [2020 Financial Modeling Competition](https://www.dcjingsai.com/v2/cmptDetail.html?id=439) by [Xiamen International Bank](https://www.xib.com.cn/english/). 

### Competition Information

#### Time Schedule

- First Round: 10/26/2020 - 12/10/2020
- Second Round: 12/11/2020 - 12/25/2020 (top 50)
- Second Round Review: 12/26/2020 - 01/10/2021
- Final Round: Pending Schedule

#### Tasks

With the development of finance and data science, banks established many contact marketing strategies, both online and off-line, in order to satisfy various customer demands, covering both regular business products and special channel trading services. Facing numerous requests, banks need to better understand customer's preferences on service selection. For daily business, they need to detect potential triggers that cause customers to leave. They also need to predict whether or not a customer will stay, given his/her financial situations. Through prediction and detection, banks can proactively provide marketing incentives to targeted customers who are likely to not retain. In this way, banks can achieve precision marketing and maximize revenues. 

This competition requires competitors to build a prediciton model based on real-world customer data. It also asks competitors to provide feasible business solutions based on their model results.

#### Team

**Team Name:** NYU A3SR

**Team Members:**

- [Tong Jin](https://github.com/tong-jin-nyu)
- [Zixuan Zhou](https://github.com/timzhou1009)
- [Zheng Tan](https://github.com/ZhengAndyTan)

## Data

The data package contains two parts: 

1. Train sets, `x_train.rar` and `y_train.rar`.

2. Test set, `x_test.rar`.

The hold-out dataset, `y_test.rar` is used to measure model performance and, therefore, is not given.

### Train Sets

The `x_train.rar` train set contains all the features. The `y_train.rar` contains the label for features. 

Train sets contain random samples of customer data in two quarters: Q3-2020 (July, August and September) and Q4-2020 (October, November and December). 

### Test Set

The `x_test.rar` contains all the features of the test sets. It has the same features as the train set. 

The test set contains random samples of customer data in the first quarter: Q1-2020 (January, February and March).

### Process

The process is to train models using the train sets and make predictions using the test set.

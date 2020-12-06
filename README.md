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

### Code Book
##### aum_m(Y) 
This data set contains customer's assest at the end of month Y.

| Variable Name | Description |
| ------------- | ------------- |
| cust_no  | custumer's ID (primary key)  |
| X1  | structured deposit balance |
| X2  | time deposit balance  |
| X3  | demand deposit balance  |
| X4  | financial products balance  |
| X5  | fund balance  |
| X6  | assest management balance  |
| X7  | loan balance  |
| X8  | large deposit certificate balance  |

##### behavior_m(Y) 
This data set records customers' behaviors in month Y.
B6 and B7 only have data of month 3, 6, 9 and 12.

| Variable Name | Description |
| ------------- | ------------- |
| cust_no  | custumer's ID (primary key)  |
| B1  | mobile banking login times |
| B2  | transfer-in times |
| B3  | transfer-in money amount  |
| B4  | transfer-out times |
| B5  | transfer-out money amount  |
| B6  | lateset transfer time  |
| B7  | number of transfers in a season |

##### big_event_Q(Z)
This data set records customers' important behaviors in the season Z.

| Variable Name | Description |
| ------------- | ------------- |
| cust_no  | custumer's ID (primary key)  |
| E1  | account opening date |
| E2  | online banking opening date |
| E3  | mobile banking opening date  |
| E4  | first online banking login date |
| E5  | first mobile banking login date |
| E6  | first demand deposit date |
| E7  | first time deposit date |
| E8  | first loan date |
| E9  | first overdue date |
| E10  | first cash transaction date |
| E11  | first bank-securities transfer date |
| E12  | first transfer at counter date |
| E13  | first transfer via online banking date |
| E14  | first transfer via mobile banking date |
| E15  | maximum amount transferred out of another bank |
| E16  | maximum amount transferred out of another bank date |
| E17  | Maximum transfer amount from other bank |
| E18  | Maximum transfer amount from other bank date|

#####  cunkuan_m(Y)
This data set contains customers' deposits in month Y.

| Variable Name | Description |
| ------------- | ------------- |
| cust_no  | custumer's ID (primary key)  |
| C1  | deposit products value|
| C2  | number of deposit products  |

#####  cust_avli_Q(Z)
This data set contains customers list in the season Z.

| Variable Name | Description |
| ------------- | ------------- |
| cust_no  | custumer's ID (primary key)  |

##### cust_info_q(Z)
This data set contains customer information in the season Z.

| Variable Name | Description |
| ------------- | ------------- |
| cust_no  | custumer's ID (primary key)  |
| l1  | gender |
| l2  | age |
| l3  | class |
| l4  | tag |
| l5  | occupation |
| l6  | deposit customer tag |
| l7  | number of products owning |
| l8  | constellation |
| l9  | contribution |
| l10  | education level |
| l11  | family annual income |
| l12  | field description |
| l13  | marriage description |
| l14  | occupation description |
| l15  | QR code recipient |
| l16  | VIP |
| l17  | online banking client |
| l18  | mobile banking client |
| l19  | SMS client |
| l20  | WeChat Pay |

### Process

The process is to train models using the train sets and make predictions using the test set.

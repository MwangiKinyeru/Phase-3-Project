# Phase-3-Project

# INTRODUCTION
This repository contains a comprehensive analysis and predictive modeling project aimed at identifying at-risk customers and informing targeted retention strategies to reduce churn and increase revenue


## Business overview
Our company is facing high customer churn, resulting in substantial revenue loss and brand damage. Current retention methods are ineffective. To address this, we need to develop a predictive model that accurately identifies at-risk customers. This model will guide targeted retention strategies, aiming to reduce churn and increase revenue.


## Business Understanding
The primary objective of this project is to reduce customer churn by accurately identifying at-risk customers using predictive modeling. By understanding which customers are likely to leave, the company can proactively implement targeted retention strategies, thereby reducing churn, minimizing revenue loss, and protecting the brand’s reputation.


#### Shareholders key questions
1. What are the main factors contributing to customer churn?
2. Which customer segments are most at risk of churning?
3. How can we improve customer satisfaction to reduce churn?
4. What are the financial implications of reducing churn?


## Data Understanding
We are going to use dataset from JB Link Telco Customer Churn which can be downloaded in [kaggle](https://www.kaggle.com/datasets/johnflag/jb-link-telco-customer-churn). We will use this data from JB Link which is a small size telecom company located in the state of California that provides Phone and Internet services to customers on more than a 1,000 cities and 1,600 zip codes. The main objective of this project is to address reasons that make customers to churn phone and internet services in the network industry. This project can be used by any network provider industry.


## dataset understanding
our dataset is known as **telco_churn_data.csv** is a csv file and contains 46 columns. we will pick just the relevant columns and drop the rest. we will have 2 models and some of the columns we will use in our model include:
1. Logistic regression - Target Variable: Churn Value, Other Variables: Tenure in Months, Monthly Charge, Internet Service, Contract.
2. decision tree model - Target Variable: Churn Value, Other Variables: Tenure in Months, Monthly Charge, Internet Service, Contract, Payment Method.
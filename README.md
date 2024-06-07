# SyriaTel Customer Churn Prediction
### Author: Nashon Okumu

## Overview

Welcome to the GitHub repository for the SyriaTel Customer Churn Prediction project. This repository contains all the code, data, and documentation for developing a predictive model to address the high customer churn rate faced by SyriaTel. The project aims to identify customers at risk of churning, understand the underlying factors driving this behavior, and provide actionable insights to improve customer retention. Using a comprehensive dataset sourced from Kaggle, the repository includes steps for data preparation, model development, evaluation, and recommendations. The ultimate goal is to build a robust model with high accuracy and recall to help SyriaTel reduce churn and enhance profitability. Explore the repository to find detailed explanations, notebook, presentations and results that guide the entire process from data exploration to deploying the predictive model.

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/0840e334-da77-45ba-a28f-a07595e8fb66)


## 1. Business Understanding

### Problem Statement
    
SyriaTel is a telecommunications company that is currently facing a very high churn rate as many customers tend to discontinue and leave their services and replacing them with their competitors. The company wants to develop a customer churn prediction model that would address this issue. SyriaTel aims to gain insights on contributing factors to the high churn rate in order to reduce it, increase customer retention and maximize the company's profits.

### Objectives
To identify contributing factors of customer churn.
To develop a model to predict customers at risk of churning.
To recommend Proactive measures for customer retention.
### Metrics
A robust customer churn prediction model with high accuracy and recall of 0.80.
Key features contributing to customer churn.
Actionable insights and recommendations to SyriaTe on churn reduction and customer retention.

## 2. Data Understanding
The dataset for this project is sourced from Kaggle (https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset). It has been downloaded directly from Kaggle's repository of datasets. Kaggle is a well-known platform for data science competitions, providing a wide array of datasets for educational and research purposes.

This dataset appears to be a single, consolidated dataset relevant to customer churn analysis. Each feature within the dataset is crucial for understanding different aspects of customer behavior and interactions with the service provider. The relevance of this dataset lies in its comprehensive nature, covering various dimensions such as service usage, financial charges, and customer support interactions, all of which are pivotal in predicting churn.

By analyzing these features, we can build predictive models to identify customers who are likely to churn, enabling the company to take proactive measures to retain them.

#### Categorical Features:

`state`: The state where the customer resides.

`phone number`: The phone number of the customer.

`international plan`: Whether the customer has an international plan (Yes or No).

`voice mail plan`: Whether the customer has a voice mail plan (Yes or No).

#### Numeric Features:

`area code`: The area code associated with the customer's phone number.

`account length`: The number of days the customer has been an account holder.

`number vmail messages`: The number of voice mail messages received by the customer.

`total day minutes`: The total number of minutes the customer used during the day.

`total day calls`: The total number of calls made by the customer during the day.

`total day charge`: The total charges incurred by the customer for daytime usage.

`total eve minutes`: The total number of minutes the customer used during the evening.

`total eve calls`: The total number of calls made by the customer during the evening.

`total eve charge`: The total charges incurred by the customer for evening usage.

`total night minutes`: The total number of minutes the customer used during the night.

`total night calls`: The total number of calls made by the customer during the night.

`total night charge`: The total charges incurred by the customer for nighttime usage.

`total intl minutes`: The total number of international minutes used by the customer.

`total intl calls`: The total number of international calls made by the customer.

`total intl charge`: The total charges incurred by the customer for international usage.

`customer service calls`: The number of customer service calls made by the customer.

## 3. Data Preparation

## Data Cleaning
Before Proceeding to the Analysis, there is need to first handle the missing values and duplicates in order to preserve integrity of the data

### Exploratory Data Analysis (EDA)

This section explores and uncovers the patterns in the dataset, and how the variables are related.

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/6c3358e4-52dc-4d8f-9b6e-17d6f902249b)


![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/b1dd25bb-f75e-4e05-8188-8ec10043ea83)


#### Distribution of Numerical Features

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/44edf66e-0352-4bc4-be64-33116f130750)


#### Distribution of Categorical Features

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/29f55808-a9cd-4115-8b4f-2da0305353ff)

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/febd2151-bfe9-4389-8e7e-23cb9a71c2e2)

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/3400e172-4a53-4c57-a5a6-a57d9fe40c9c)

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/6b304fd8-4b65-43dc-a324-6fe4faad0c1f)

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/62a8999a-f78b-4570-9215-893551025b43)

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/5e67ac2f-004b-4aea-8d0a-60885dff015c)

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/68962d0a-c592-4166-98e1-97f2f3bafede)

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/c664d1ec-0999-4a77-9340-f4d50e37c8c0)

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/274be5a6-6af7-46b0-8a22-4727e881d7ce)

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/132b293f-fc07-4bbe-9560-83087aa9fbef)

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/8531b396-c39f-417b-b7d1-fa265e41423b)

### Correlation Analysis

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/15ea930a-9ca1-403a-80f2-710ced30a630)


## 4. Modeling

### Logistic Regression 

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/4ee49d75-bd7c-4e39-8c5b-fe4e93105da4)


### Decision Tree

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/b7145672-db69-436d-b3bc-650fe84496da)

### Random Forest

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/3424323f-5c6a-4353-a97c-a82eb8e2d1dd)


### XG Boost

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/7d420ee6-17d5-445f-8816-87beffccf6ce)


## 5. Model Evaluation

## Feature Importances

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/6e325ff1-625b-4ffb-9f7e-7ff6aeb39b1b)


### ROC Curves

![image](https://github.com/NashonOkumu/churn-prediction/assets/66790358/8bf0a870-259e-4fdc-85b1-a30ea9328896)

## 6. Conclusion

The XG Boost Classifier has the highest recall score of 0.8 that is 80%. It is also the best performing model according to the ROC curve. We achieve the objective as the model is able to predict customer churn at the expected recall score.

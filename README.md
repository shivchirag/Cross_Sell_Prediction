# Cross_Sell_Prediction

Hello, all. We have worked on the Health Insurance Cross Sell Prediction dataset of an insurance company. The dataset contains information of various customers like whether they have had a vehicle insurance, whether they have a driving license, what is their annual premium amount and many more relevant things. 

It also contains informations on the region the customer belongs to and the method used to close the vehicle insurance sale.

We have tried to work on the data and get three things out of it:

a. We have tried to generate insights through the EDA process

b. We have tried to analyse the kinds of relations between a sale being closed and the customer data

c. And most importantly, we have tried to build a machine learning predictive model that helps us predict the customers who may lean towards buying our vehicle insurance in future.

We hope that you like the project and we would like to listen to your thoughts on it. You can reach us at shivchirag1997@gmail.com and er.tapomay@gmail.com

## Problem Statement

Our client is an insurance company who wish to sell their health insurance customers vehicle insurance. And they have provided us with the dataset from their first attempt. We are supposed to find insights from their first attempts and then build a predictive model to predict which customers in future are more likely to buy their vehicle insurance.

## Dataset

The dataset has 381109 rows and 12 columns. It has no duplicated rows and zero null values.

Apart from the target variable, there are six other categorical variables and the rest are numeric (discrete and continuous).

**id :** Unique ID

**Gender :** Gender of the customer

**Age :** Age of the customer

**Driving_License :** Does the customer have a driving license?

**Region_Code :** Unique ID of the region of the customer

**Previously_Insured :** Did the customer previously have a vehicle insurance?

**Vehicle_Age :** Age of the customer's vehicle

**Vehicle_Damage :** Is the customer's vehicle damaged?

**Annual_Premium :** Amount customer pays as premium annually

**Policy_Sales_Channel :** Policy Sales Channel (Anonymised code)

**Vintage :** Number of days customer has been with the company

**Response :** Response (Target Variable)

## Data Cleaning and Wrangling

We dont think the dataset needs to be divided anymore or worked much upon for the EDA process. We are very happy with what we have and decided to divide the dataset only based on the final response of the customer.

## EDA Process

We did an extensive analyis of the dataset using charts like heatmap, barplot, scatterplot, line plot and pie chart. These were used to do multiple univariate, bivariate and multivariate analysis. For the insights generated, please look at the presentation.

## Predictive Modeling

We created a classification model using the Gradient Boosting Algorithm. It gives us the ROC AUC score of 0.80, recall of 0.94 and the precision value of 0.28. And it also makes the use of a lot of the newly created features of ours and distributes the importance of the features more evenly throughout the dataset.

For more on the process and the results, would recommend to go through the project notebook uploaded and/or the final presentation prepared.

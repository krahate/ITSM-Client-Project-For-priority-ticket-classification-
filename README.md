# ITSM-Client-Project-For-priority-ticket-classification-

# Problem Statement
ABC Tech is an mid-size organisation operation in IT-enabled business segment over a decade. On an average ABC Tech receives 22-25k IT incidents/tickets , which were handled to best practice ITIL framework with incident management , problem management, change management and configuration management processes. These ITIL practices attained matured process level and a recent audit confirmed that further improvement initiatives may not yield return of investment.ABC Tech management is looking for ways to improve the incident management process as recent customer survey results shows that incident management is rated as poor.Total of about 46k records from year 2012,2013,2014

1. Predicting High Priority Tickets: To predict priority 1 & 2 tickets, so that they can take preventive measures or fix the problem before it surfaces.

2. Forecast the incident volume in different fields , quarterly and annual. So that they can be better prepared with resources and technology planning.

3. Auto tag the tickets with right priorities and right departments so that reassigning and related delay can be reduced.

4. Predict RFC (Request for change) and possible failure misconfiguration of ITSM assets

## About Dataset

This project belongs to ABC technologies, where the company wanted to include the ML algorithms for the automatic prediction of priority tickets. Data needs to be queried from MYSQL data base (Read Only Access)

## Workflow of the project:

1. Reading the data from server  

2. Saving the data into a local drive 

3. Analysing the data & Exploratory Data Analysis 

4. Data Cleaning and Data mugging 

5. Modeling

The project is done with the purpose of:

Finding out factors which affects priority and training a model which accurately predicts it so that preventive measures can be taken for High Priority Tickets and reassigning can be reduced.
Finding out factors which affect RFC and predicting it.
Forecasting Incident Volume in the future so that they can be better prepared with resources and technology planning.

The analysis is done in three parts:

1. Predicting Priorities

2. Predicting Request for Change (RFC)

3. Forecasting the Incident Volume

## Analysis

The data is ordinal, nominal as well as categorical. To analyze the data, various data processing techniques like Label Encoding and Standardization is used.For training the data and predicting the target, algorithms used are Support Vector Machine, Decision Tree, Random Forest, Logistic Regression and XGBoost Classifier. Volume Forecasting is done with the help of Statsmodels & Matplotlib.

The analysis is done in three parts:

1. Predicting Priorities

2. Predicting Request for Change (RFC)

3. Forecasting the Incident Volume: The predictor variable is opening time.

## Summary

The project is done with the purpose of:

1. Finding out factors which affects priority and training a model which accurately predicts it so that preventive measures can be taken for High Priority Tickets and reassigning can be reduced.

2. Finding out factors which affect RFC and predicting it.

3. Forecasting Incident Volume in the future so that they can be better prepared with resources and technology planning.

## Results

For predicting Ticket Priority, Random Forest gives almost 99% accuracy. Predicting RFC accurately is not possible with this data as the missing value is more than 90% still we have imputed with the mode which is not best practise. And Volume Forecasting is visualized with the help of Matplotlib throughout the year.

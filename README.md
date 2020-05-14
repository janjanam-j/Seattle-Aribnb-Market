# Seattle-Aribnb-Market
Seattle Airbnb Market- A brief overview

Table of Contents
1. 



Objectives/Motivation of the Analysis:

Presuming myself to be a prospective Airbnb host in a city like Seattle, I would like to understand the basic aspects of the Seattle Airbnb market:
What are the key factors that impact the listing price?
What are the popular and least popular neighborhoods?
Is there a seasonal pattern in the price of the listings?
A brief layout of the analysis is as follows:
Datasets used: The datasets listings and calender provide enough information to answer the aforementioned questions.
Data Source: Kaggle generously provided the information of the listings and price by calendar days for Seattle which are used in the current analysis.
Cleaning the listings dataset:
Columns with missing values are identified and columns with 20% or more missing information are listed.
Columns that do not provide any information related to the questions, columns with too much variation, and no variation are gathered by reviewing the categorical and numeric variables.
Columns identified in a and b are dropped.
Columns with special characters are cleaned and a clean data set for exploratory analysis is prepared.
Cleaning the calendar dataset
Special characters are replaced and appropriate variables are converted to their specific data types.
The date variable is decomposed to months, days, and weekdays to understand the seasonal patterns.

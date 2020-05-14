# Seattle-Aribnb-Market
Seattle Airbnb Market- A brief overview

Table of Contents
1. Objectives of the analysis
2. A brief layout of the analysis
3. Results
4. Future work



Objectives/Motivation of the Analysis:

Presuming myself to be a prospective Airbnb host in a city like Seattle, I would like to understand the basic aspects of the Seattle Airbnb market:

1. What are the key factors that impact the listing price?
2. What are the popular and least popular neighborhoods?
3. Is there a seasonal pattern in the price of the listings?

A brief layout of the analysis is as follows:

Datasets used: The datasets listings and calender provide enough information to answer the aforementioned questions.

Data Source: Kaggle generously provided the information of the listings and price by calendar days for Seattle which are used in the current analysis.

Cleaning the listings dataset:

1. Columns with missing values are identified and columns with 20% or more missing information are listed.
2. Columns that do not provide any information related to the questions, columns with too much variation, and no variation are gathered by reviewing the categorical and numeric variables.
3. Columns identified in a and b are dropped.
4. Columns with special characters are cleaned and a clean data set for exploratory analysis is prepared.

Cleaning the calendar dataset:

1. Special characters are replaced and appropriate variables are converted to their specific data types.
2. The date variable is decomposed to months, days, and weekdays to understand the seasonal patterns.

Results:

1. Bathrooms, bedrooms, beds, number of guests the listing can accommodate, and the number of reviews provided by previous guests seems to play an important role in pricing the listing.
2. Other factors that influence the price are host response time, property type, rented room type, type of beds shared, cancellation Policy, and guest verification
3. Southwest Magnolia is the most expensive neighborhood_cleansed while Rainier Beach is the cheapest.
4. There is a gradual increase in the price from January and peaked from July to September followed by a decrease towards the end of the year.
5. Weekends are expensive compared to weekdays.

Future Work:

1. Considering these key indicators as predictors of the price. However, further data cleaning is needed. A few aspects the need to be considered are

2. There are a few predictors numeric variables that are highly correlated with each other. So, while performing the prediction analysis, these should be taken into consideration, and variables of less importance should be dropped to exclude any existing multicollinearity.

3. A few categorical variables for instance-neighborhood has 81 unique categories. While creating dummy variables, this alone will create about 80 variables. A deep analysis and grouping the neighborhoods with some logic- like group them by county, etc. So, all categorical variables with too many categories should be broken down logically before creating dummy variables.

4. Amenities do have an impact on the price. However, this variable needs an extensive de-cluttering, identifying which combination of amenities are associated with the high pricing listing…. etc


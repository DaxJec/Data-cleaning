# Data-cleaning
Acquainting ourselves with data cleaning
# Introduction to Data Cleaning

The purpose of this project is to acquaint ourselves with knowledge required to prepare our dataset for modeling phase.

The modeling could be related to buidling a machine algorithm or building a business intelligence report (dashboard)

It is crucial understand the features that constitute the dataset. This helps us to be able assign the appropriate data types

for the different features respectively.

##### Review comments

* for the features,dateCrawled,dateCreated and lastSeen are date columns. We are interested in having the dates without time (extracting the date from the datetime timestap)

* the price and odometer are supposed to be numerical. For price, we must remove the comma and the dollor sign, and convert the column to int. Odometer, we must remove the comma and km 

* yearofRegistration and monthofRegistration have to be in string type as they can not be aggregated (convert from int to string)

* convert the postal code to string (it can not be aggregated as well)

* modifying the feature names

* Handling the missing values for the categorical features

* Creating a function that handles the data cleaning at once

* saving the newly cleaned dataset for future use

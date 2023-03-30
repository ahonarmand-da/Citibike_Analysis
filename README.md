# Citibike Data Analysis

## Introduction

Citibike is a bike sharing service that allows users to rent bikes from stations located throughout the city. In this project, I will be analyzing data from Citibike to answer various questions about bike usage and user demographics.

Data Collection

The data was provided in the form of a CSV file which contained information about trips taken on Citibike between 2013 and 2019. The data was imported into a SQLite database for analysis.

## Data Cleaning
Before performing any analysis, the data was cleaned to ensure that it was in a usable format. This involved removing any missing values, converting data types, and making sure that the data was consistent.

## Data Analysis
The following questions were analyzed using SQL queries:

What are the busiest stations in terms of bike usage? Are there certain stations that are more popular for starting trips, or for ending trips?
How has the usage of Citibike changed over time? Is there a particular year or season when usage is higher or lower?
Is there a correlation between the age or gender of the rider and the duration of the trip?
What is the average trip duration for different customer plans (such as annual members versus day pass holders)? Are there certain plans that tend to use the bikes for longer or shorter trips?
The results of the analysis showed that:

The top 10 busiest starting and ending stations had between 2939 to 4139 trips.
Usage of Citibike was highest in the summer, with the summer of 2017 being the busiest season with 52,705 trips. The winter of 2013 had the lowest number of trips with only 4,517 trips in total.
On average, males use the bikes for about 13 minutes whereas females use the bikes for about 15 minutes and 31 seconds. The unknown group have used the bikes for 31 minutes and 51 seconds. The distribution of the male and female is not clear in the unknown group.
The “Customers” are using the Citibike more than the “Subscriber”. Additionally, the female costumers are the top users of Citibike, using the bikes on average for about 51 minutes.

## Conclusion
The analysis of Citibike data showed interesting insights into bike usage and user demographics. Further analysis could be done to explore other aspects of the data, such as user age and the popularity of different bike models. Overall, the project showed the power of data analysis in understanding trends and making data-driven decisions.

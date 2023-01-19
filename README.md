# Amazon_Vine_Analysis

## Overview of the analysis: 
The purpose of this challenge was to analyze the Amazon reviews written by members of the paid Amazon Vine program and to determine if there is any bias towards any favorable reviews from Vine members using PySpark to do the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.

## Results: 

- Total Vine reviews (paid) = 647.
- Total non-Vine reviews (unpaid) = 74113.
- Total five star paid reviews = 229.
- Total five star unpaid reviews = 43217.
- Percentage five star paid reviews = appoximately 35.4%.
- Percentage five star unpaid reviews = appoximately 58.3%.


## Summary: 
I would say positivity bias for reviews in the Vine program is present because of the huge difference in the total number of vine and not vine reviews.
Additional analysis can be made with the Market place and the verified purchase columns to provide better analysis and hopefully lesser bias.

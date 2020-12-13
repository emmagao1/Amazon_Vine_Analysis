# Amazon_Vine_Analysis
 
## Overview

The purpose of this analysis is to perform the ETL process to extract dataset and store it with Amazon Web Services (AWS). The dataset is from a Amazon Customer Review database that contains two types of customer feedback: paid and unpaid reviews. This dataset includes information about various watches from an Amazon program called Vine that was responsible for conducting the paid reviews.

Software: Python with PySpark in Google Colaboratory (used to transform and clean the dataset), pgAdmin with SQL tables, and AWS servers.

## Results

* There were 8,409 total reviews. There were 47 total paid Vine reviews and 8,362 unpaid reviews.

* There are only 15 five star Vine reviews. There are 4,332 five star unpaid reviews.

* 31.9% of Vine reviews were five stars. 51.8% of non-Vine reviews were five stars.

## Summary

* There are 47 total reviews for the paid program, compared to 8,362 unpaid reviews.

* There is negative bias for the paid reviews, as the % to total of 5 star reviews was only 31.9% compared to unpaid at 51.8%. 

* Additional analysis we can perform is to check if vine reviews have any impact on helful votes as vine program might alter people's view on how to vote on the reviews.




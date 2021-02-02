# Amazon_Vine_Analysis
Week 16 Challenge

## Project Overview
In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

## Results

Paid Results
* 1. Total Paid Review Count = 94
* 2. Vine Paid 5-Star Review Count = 48
* 3. Vine Paid 5-Star Review Ratio (total 5 star reviews / total reviews) = 0.51

Unpaid Results
* 1. Total Unpaid Review Count = 40,471
* 2. Vine Unpaid 5-Star Review Count = 15,663
* 3. Vine Unpaid 5-Star Review Ratio (total 5 star reviews / total reviews) = 0.387

## Summary
The results show that there may be some bias but not to the level that would raise eyebrows. The difference between the ratio of 5-star reviews from paid to unpaid users is 0.51 to 0.387, which results in a spread of ~0.13.



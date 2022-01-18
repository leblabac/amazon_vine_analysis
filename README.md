# Amazon_Vine_Analysis

## Overview of the analysis  
In this project I selected a data set from Amazon Reviews regarding Amazon Gift Cards, and used PySpark to perform the ETL process by extracting, transforming and loading the data generated for me through the AWS webserver to a PostGres database. 

A dataframe was created to retrieve all the rows where there were 20 or more total votes, after which it was filtered to retrieve rows where the number of helpful votes divided by the number of total votes was equal to or greater than 50%.  

## Results   
### How many Vine reviews and non-Vine reviews were there?
Based on the initial two queries, it was identified that there were 355 reviews. Of the 355 reviews, 0 were Vine (paid) reviews.

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
There were no Vine reviews that were 5 star reviews. Within the 355 non-Vine reviews, there were 90 that were 5-star rated.

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Given the results above, there was no percentage of 5 star reviews that were paid (Vine) reviews.
Approximately 25% of the reviews that were made were 5-star reviews.

## Summary
Based on the lack of Vine (paid) reviews within the dataset, there does not appear to be any sort of positivity bias.

# Amazon_Vine_Analysis

## Overview

For this project, using PySPark, I chose one of the fifty datasets provided to perform at ETL process of extracting the chosen dataset, tranform the data, connect it to an AWS RDS instance, and load the transformed data into PGAdmin. Then, using PySpark, the objective was to determine if there was any bias toward favorable reviews from Vine members in the dataset. 

## Analysis
- How many Vine reviews and non-Vine reviews were there? There were a total of 94 paid reviews. As far as the unpaid reviews, there were 40471. 
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars? There were a total of 48 paid 5 star reviews. As far as the unpaid 5 star reviews, there were 15663. 
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars? The percentage of paid 5 star reviews was about 51.1%. The percentage of unpaid 5 star reviews was about 38.7%. 

## Summary 
- I do not see any bias here. With the number of 48 paid 5 star reviews comapred to the 15663 unpaid reviews, there does not seem to be a case for positivity bias in this data. A further analysis that could be performed would be to look at all of the products and not just the subset of data that was analyzed in this report to determine if all products see a case for positivity bias. This subset of data could just be the exception. More analysis would be needed to determine if that is the case. 

# Amazon_Vine_Analysis
## Overview of the project
Using PySpark, AWS and PostgreSQL to analyse the dataset for Amazon Vine Reviews. Using these tools, I built an ETL pipeline and anlysed the reviews to understand the number of 5 star reviews

### Tools Used
- Dataset: Home Improvement Category product reviews: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Home_Improvement_v1_00.tsv.gz
- Software:
  - Google Collab
  - AWS
  - PostgreSQL
  - PySpark

## Results
### How many vine reviews and non-vine reviews were there
In this particular ccategory of Home Improvement, there we not many Vine reviews. Below are the stats
- total vine reviews: 266
- total non-vine reviews: 38,829

Clearly from the above data we can infer that the number of non-vine reviews were far greater than the vine reivews  
### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
From the data set we can see that
- Vine 5-star reviews: 125
- Unpaid(non-vine) 5-star reviews: 18,246

### Percentage
- Paid Vine 5-star percentage: 46.99%
- Unpaid Vine 5-star percentage: 46.99%

## Summary
From the above data, we can clearly see that the paid vine reviews for the Home Improvement category did not work and had no positivity bias.  
To validate this even further, we can look at, the number of people with paid and un-paid categories who had a verified purchase to see if that affects the results.

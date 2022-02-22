# Amazon_Vine_Analysis

## Overview

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. We used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Summary of the analysis for Jennifer to submit to the SellBy stakeholders. I analyzed the musical instruments dataset.

## Results

The three questions we're trying to answer here are:

- How many Vine reviews and non-Vine reviews were there?
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

#### How many Vine reviews and non-Vine reviews were there?
![snippet 1](https://github.com/l-javier-garcia/new-repo/blob/main/Module%2016%20snippet.PNG)

#### How many Vine were 5 stars? How many non-Vine reviews were 5 starts?
![snippet 2](https://github.com/l-javier-garcia/new-repo/blob/main/module%2016%20snippet%202.PNG)

#### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
![snippet 3](https://github.com/l-javier-garcia/new-repo/blob/main/module%2016%20snippet%203.PNG)

## Summary

There were a total of 572,916 reviews, there were more non-Vine reviews than Vine reviews and also a lot of the non-Vine reviews were considered helpful than the Vine reviews. 

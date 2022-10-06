# Amazon_Vine_Analysis
# Overview:
### Analyzing Amazon reviews written by members of the paid Amazon Vine program.
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. We will choose one product category data set and perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then, we will use PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset.

# Results:
The product category data set that was used for this analysis was the Outdoors category.

The table below shows the results of the analysis:


# Summary
Bias of Vine member reviews was not present due to the consistent percentages of 5-star reviews found in the three groups. Simple rounding shows all three groups had roughly 53% of their reviews rated at 5 stars.

### Addition Analysis to consider
* Percentage of Vine/Non-Vine reviews that were negative or below 2 stars
* Natural Language Processing (NLP) to analyze the sentiment of each review to predict future reviews

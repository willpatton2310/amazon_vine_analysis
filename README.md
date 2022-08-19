# amazon_vine_analysis

## Objective
The purpose of this exercise was to evaluate the Amazon Vine program which allows companies to receive reviews for their products.  For his exercise, we chose the automotive dataset, used PySpark to perform the ETL, and ran analysis on how many good reviews were made to see if there s a bias from Vine members in the data set.

## Results
Our analysis showed that there were a total of 76 vine reviews and 22,972 vine non-reviews for our dataset.  This would indicate that our vine program is not working so well.  Of the vine reivews, 30 (39.4%) were 5 star.  Of the non-vine reviews, 11,908 (51.8%) were 5 star.  There seems to be a positivity bis for the non-vine reviews.  As an additional analysis, we might consider using Tokenizing capabilities of PySpark to do natural language analysis of the comments under the "review_headline" column to dig deeper into the feedback from customer.

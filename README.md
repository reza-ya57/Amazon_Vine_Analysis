# Amazon_Vine_Analysis

# Overview of the analysis
## In this study we compare the Vine Program review and regular member reviews on the different model of cameras which is provided by Amazon website.
### What is Vine program?
#### The Amazon Vine Program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.
# Goal of this study
## Identify any positivity bias for reviews in the vine program. To cover this goal we are going to answer below question:
### How many Vine reviews and non-Vine reviews were there?
- Vine reviews: There were 579 Vine reviews in total for this study
- non_Vine reviews: There were 47521 non-Vine reviews in total for this study

![total_review](https://github.com/reza-ya57/Amazon_Vine_Analysis/blob/main/total_review_paid_unpaid.png)
### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- Vine reviews: Totaly there were 246 reviews with 5-star rating in Vine program
- non-Vine reviews: Totaly there were 23816 reviews with 5-star rating in non-Vine program
- Also in case that you want to comare the other grade of reviews you can check below tables which are show the total number of review per each rating star for each Vine and non-Vine program.
### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- Vine program: In vine program almost 42% of the reviews are 5-star
- non-Vine program: In non-vine program almost 50% of the review are 5 star




For this part of the Challenge, you’ll write a report that summarizes the analysis you performed in Deliverable 2.

The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images of DataFrames as support, address the following questions:

Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the

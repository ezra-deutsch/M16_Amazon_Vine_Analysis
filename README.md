# Amazon_Vine_Analysis - Module 16 - Challenge

### Overview and Purpose

The purpose of this analysis was to combine technologies (PySpark, Google Colab, AWS, and Postgres) to be able to wrangle and analyze Big Data. Given a dataset of our choice, in this case Amazon reviews for Electronics, we needed to parse the data between different subsets, and analyze the product reviews. Vine members are paid for their reviews, so with a little analysis, we can see if their compensation is giving us bais reviews.

### Results

Overall Helpful Reviews-
* Total Number of Reviews: 			50,753
* Total 5 Star Reviews:				23,497
* % of Total 5 Star Reviews:			46.29%

Helpful Vine Reviews-
* Total Number of Vine Reviews:			1,080
* Total 5 Star Vine Reviews:			454
* % of 5 Star Vine Reviews:			42.04%

Helpful non-Vine Review-
* Total Number of non-Vine Reviews:		49,673
* Total 5 Star non-Vine Reviews:		23,043
* % of 5 Star non-Vine Reviews:			46.39%

(![vine_review_stats](https://user-images.githubusercontent.com/88510296/143687432-73633351-0f7e-4b32-8322-2e7ed1111143.png)
)


### Summary

Based on this analysis of product reviews we cannot say that there is any bias in positive reviews for the Vine program. The rate of 5 Star reviews was less for Vine members (42.04%) than non-Vine members (46.39%).

An interesting additional analysis that could be run on the dataset would be Natural Language Processing. Adding an analysis of the words used by the reviewer in the "review_body" column, would help us go above and beyond just a simple star rating analysis and could help us fine tune our product analysis. 

Web Link: (https://github.com/ezra-deutsch/M16_Amazon_Vine_Analysis)

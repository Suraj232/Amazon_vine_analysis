# Amazon_vine_analysis
## Overview of Analysis
The purpose of this analysis is to study about the reviews written by the paid and unpaid vine member. This reviews helps the manufacturer to determine if their is any biased approach by paid and unpaid members.

This analysis is done by using different tools and platforms:
Extract and transform the data via Pyspark and then connect to AWS RDS and load the data into PgAdmin.
The vine analysis can be carried out in Google Colab, Pyhton, and SQL. This analysis is done in Google Colab.

## Result
1.) How many Vine and non-Vine reviews where there?

- Vine members made up only .55% of reviews where as non-Vine members account to 99.45% which is (8362) as shown in the figure.
<img width="414" alt="Vine" src="https://user-images.githubusercontent.com/110261837/208826707-664ccd59-763b-4950-b117-e3d348fb7989.png">

2.) How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- Out of 47 Vine members only 15 members review accounts to 5 star rating. 
- Out of 8362 non-Vine members only 4332 members review accounts to 5 star rating.

3.) What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- 31.91% of vine members gave 5 stars rating.
- 51.81% of non-vine members gave 5 star rating.

## Summary
- As we see the result, vine members didnt show any bias when it came to rating the product. Their is 20% difference between vine and non-vine members, non-vine members being on the higher end. This shows that vine customers are more considerate while submitting the review. 
- The analysis would have been better if we could consider whole data rather than filtering the data which we did in the beginning of the analysis.

# Amazon Vine Analysis

## Overview

Our company, BigMarket, has been hired by a company called SellBy. Our client is looking to research product reviews on Amazon. They would like overall information by category, but they would also like more information about the Amazon Vine program. This program requires the program users to publish reviews on products. SellBy would like to see if this program is worth the additional fees paid by them to Amazon. 

## Results

For this part of the project, we reviewed the results for the jewelry category. 

Source: https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt

Jewelry URL: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Jewelry_v1_00.tsv.gz

- How many Vine reviews and non-Vine reviews were there?
  - Total reviews: 1,767,753
  - Total Vine reviews: 3,815
  - Total non-Vine reviews: 1,763,881
  - Total null values: 57 
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - Vine 5-star reviews: 1,724
  - Non-Vine 5-star reviews: 1,079,726
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - Vine 5-star reviews percent to total: 45.2%
  - Non-Vine 5-star reviews percent to total: 61.2% 

See Image for details: 

![Vine_Results](https://user-images.githubusercontent.com/116031639/220822569-5ef324df-5cc0-4cb2-bd8f-c9e976d24a18.png)

## Summary 

Based on the results of the percent to totals, the Vine reviews did not produce more 5-star reviews than the non-Vine group, therefore there is not a positivity bias for Vine reviews. Additionally, the non-Vine group produced significantly more reviews overall. As a result of these findings, for the jewelry segment, it would not benefit SellBy to pay for the Vine program. 

One additional analysis that would be helpful would be to create a bag-of-words or BoW model. For this model, we would use the text from the reviews as well as the star-rating. The model would benefit from creating filters by star-rating so that we can see which words appear in positive and negative reviews. This will allow SellBy to see trends in customer sentiment as well as areas of excellence and areas for improvement in our products. 

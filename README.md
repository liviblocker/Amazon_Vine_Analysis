# Amazon_Vine_Analysis
## Overview Analysis
For this project, I analyzed Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. I looked at Outdoor products on Amazon: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Outdoors_v1_00.tsv.gz

## Results
As you can see in the results below, there are only 107 Vine reviews for outdoor products in contrast to the 39,869 unpaid reviews. The number of 5-star Vine reviews was only 56, while the number of 5-star unpaid reviews was 21,005. The percentage of 5 star reviews for both Vine members and unpaid reviewers was around 52%, with Vine members coming in at 52.3% and unpaid reviewers at 52.7%.

<p align="center"> Vine Reviews </p>
<p align="center">
  <img src="https://github.com/liviblocker/Amazon_Vine_Analysis/blob/main/images/Vine_Votes.png" width="600" />
</p>

<p align="center"> Unpaid Reviews </p>
<p align="center">
  <img src="https://github.com/liviblocker/Amazon_Vine_Analysis/blob/main/images/Unpaid_Votes.png" width="600" />
</p>

## Summary
There does not appear to be any positivity bias for reviews in the Vine program. While there are significantly fewer reviews through the Vine program, both paid and unpaid reviewers gave 52% 5-star rating for outdoor products. Another analysis that may be helpful in determining bias would be to look at 1-star reviews and determine if Vine member gave fewer 1-star reviews than unpaid reviewers.

# Amazon_Product_Review_Analysis

## Overview

This analysis combined Amazon product review data, AWS, Google Collab, and PGAdmin using Postgres SQL. The purpose of this analysis was to determine if there was a difference in paid (called the Vine program) vs. unpaid 5 star reviews given to products in the electronic category. The dataset was filtered to view only 5 star results and reviews that were found to be helpful to the community of 20 or more votes with a ratio of greater than or equal to 0.5 for helpful votes to total votes.

### AWS Connection
![image](https://user-images.githubusercontent.com/79415699/120951160-322dc380-c716-11eb-9e3d-ba23ed4a2c96.png)


### PGAdmin Query
![image](https://user-images.githubusercontent.com/79415699/120951168-38bc3b00-c716-11eb-8131-b3dbd8eeab77.png)


### Google Collab Analysis
![image](https://user-images.githubusercontent.com/79415699/120951098-19251280-c716-11eb-9338-9fe01d4fab7e.png)


## Results
From the extracted dataset in the electronic category, two datasets were created, paid vs. unpaid Amazon reviews.

- There were 1,080 total paid (Vine) reviews and 49,673 total unpaid reviews I analyzed.
- There were 454 paid (Vine) 5 star reviews and 23,043 unpaid 5 star reviews.
- The percentage for paid (Vine) 5 star reviews to total paid reviews was 42.04% and the percentage for unpaid 5 star reviews to total unpaid reviews was 46.39%.

## Summary
This analysis shows there was no positivity bias for reviews in the paid (Vine) program with unpaid reviews showing a slightly higher percentage of 5 star reviews. One additional test I could do to make sure there was no positivity bias would be to filter results based on viewing reviews only for verified purchases as this would be an additional step to make sure the reviewer actually purchased the product and did not just leave a review.

# Amazon_Vine_Analysis
## Overview of the Analysis
In this analysis I was tasked with analyzing Amazon reviews written by members with a paid Amazon Vine membership.  The Amazon Vine program provides manufacturers and publishers to receive reviews for their products.  Companies pay a small fee to Amazon to utilize this service.  In this analysis, I chose the shoe review dataset from Amazon.  From this dataset, I used PySpark to perform ETL in order to determine if the paid Vine customers reviews were biased.

## Results
* How many Vine reviews and non-Vine reviews were there?
 There were total of 1,079,287 Vine reviews.  
 ![Screenshot 2023-03-22 102454](https://user-images.githubusercontent.com/45715246/226935120-fe1f7bb6-e27b-4920-803d-31f2d1fbb1ab.png)

 
 Of those Vine reviews, 439 were paid Vine reviews and 1,078,848 were unpaid.

### Total paid/unpaid vine reviews screenshot:
![Screenshot 2023-03-22 101922](https://user-images.githubusercontent.com/45715246/226933424-1cf6bf6f-1975-4ee2-8905-fca01f7d8191.png)



* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

### 5 star reviews screenshot:
![Screenshot 2023-03-22 101323](https://user-images.githubusercontent.com/45715246/226931639-5511aedc-17cb-4bd3-bd72-a67b355a115d.png)


![Screenshot 2023-03-22 100742](https://user-images.githubusercontent.com/45715246/226930190-57dba825-bb98-41bb-868d-8ee982ea98db.png)

## Summary

In my opinion, I do not think the paid Vine members reviews are biased.  There were a total of 594,295 5 star rated reviews, and of those only 221 of them were paid Vine members.  That is only .04% so that means 99.96% of the 5 star reviews were made by non-Vine paid members.  Based on these results, I think people are willing to give 5 star reviews based on whether or not they like the product.  Not whether or not they are a paid Vine members. 


In addition to this analysis, I would be interested to go the other direction and do an analysis determining how many paid Vine members gave a 1 star review.  I think by doing that analysis, it would help to determine if the Vine reviews were biased or not.  I believe this would help determine the level of bias because it would show if members were or were not feeling pressure to give a great review.








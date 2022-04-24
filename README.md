# Vine Review Analysis
## By: Stacey Booysen

For this analysis, we worked through a list of reviews for Musical Instruments from Amazon. With the implementation of the ‘Vine’ program, a paid review service in which Amazon will send out products to members, we are trying to determine if the reviews are in any way skewed.
For instance, how many reviews are there that are NOT Vine reviews? What does it mean when there’s more of one over the other? There are a total of 14533 ‘helpful’ reviews but only 60 of them were from Vine members. This leaves 14473 reviews by unpaid customers that were considered ‘helpful’ by the general public. In the chart below, we can see that the top 20 most helpful reviews all came from unpaid customers.

![alt text](https://github.com/sbooysen/Amazon_Vine_Analysis/blob/main/Amazon_Vine_Analysis/Resources/Top_helpful_reviews1.png)

This could indicate that the majority of the Vine reviews might not have given other customers a clear picture of an instrument’s pros and cons, suggesting that perhaps they were slightly biased. In this way, it could be said that the Vine reviewers are consciously or unconsciously leaving reviews that others have found to be incompatible with their own experiences with the same product. 
At the same time, the amount of upvotes for helpfulness of review, seem to be higher for the Vine customers. Comparing the top 20 helpful results from the Vine reviewers and unpaid reviewers, the Vine reviewers have a more drastic number of people who said their review was helpful:

Unpaid Reviewers:
![alt text](https://github.com/sbooysen/Amazon_Vine_Analysis/blob/main/Amazon_Vine_Analysis/Resources/Top_helpful_reviews2.png)


Vine Reviewers:
![alt text](https://github.com/sbooysen/Amazon_Vine_Analysis/blob/main/Amazon_Vine_Analysis/Resources/Top_helpful_reviews3.png)


Looking at the totals of five-star reviews overall, adds a bit of complexity to the situation. The total number of five-star reviews for unpaid customers is 8244 while there are only 34 five-star reviews from Vine customers. This adds in the question of percentage—if there are fewer paid reviewers than there are non-paid reviewers, then the numbers at face value will be drastically different and provide incorrect assumptions at a glance.

As a result, we need to take the percentage of each group’s five-star reviews to really see if there’s a big difference or not. 

* Vine five-star reviews-
  * 56.667%
* Unpaid five-star reviews-
  * 43.274%
 
With this, we can see there’s about a 13% difference between the two groups. It could show an indication that Vine reviewers are a somewhat more likely to leave five-star reviews compared to unpaid reviewers. However, the difference between them may or may not create a large impact. 
When we take the totals overall, out of all five-star reviews, the majority of those reviews came from unpaid customers at 75.97% while the paid customers’ five-star ratings came to 0.412% out of the total five-star count.

To further analyze the potential of bias in this dataset, we could also factor in ‘verified purchase’ data. Since this is one of the few ways to confirm that the product has at least been sent to the customer, it would be the best way to filter out reviews that might be fake or there as a joke.
There is also the fact that Vine customers are often sent items for free, making their ‘unverified purchase’ status questionable. There are a multitude of different ways to filter and group the reviews to try and account for this, such as only filtering out the unpaid reviewers’ who have no verified purchase. This goes on the assumption that the Vine reviewers with unverified purchases, still received the items since they were being paid to review them and as a result, they are less likely to leave a fake or joke review.

Many factors go into play here but there are also many ways to divide them out and analyze them in order to get a better understanding of the effects of the Vine program.

# Amazon_Vine_Analysis

## Overview 

I have been tasked with analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, I had access to approximately 50 datasets. Each one contained reviews of a specific product, from clothing apparel to wireless products. I picked one of these datasets and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used PySpark to determine if there was any bias toward favorable reviews from Vine members in my dataset. Lastly, I wrote a summary of the analysis to submit to the SellBy stakeholders.

## Results:
**- How many Vine reviews and non-Vine reviews were there?**

Vine Reviews: 

<img width="280" alt="Screen Shot 2021-12-02 at 2 05 49 PM" src="https://user-images.githubusercontent.com/88408350/144510749-993184ce-2416-401a-8de3-2d55789b53f2.png">

Non-Vine reviews: 

<img width="349" alt="Screen Shot 2021-12-02 at 2 07 19 PM" src="https://user-images.githubusercontent.com/88408350/144510940-96e66378-1008-4cb1-90ae-c4fce9f2e08d.png">



**- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?**

5 star Vine reviews: 

<img width="582" alt="Screen Shot 2021-12-02 at 2 08 51 PM" src="https://user-images.githubusercontent.com/88408350/144511132-3b7794ab-362a-4c55-96aa-b99af7f27949.png">


5 star non- Vine reviews: 

<img width="675" alt="Screen Shot 2021-12-02 at 2 08 58 PM" src="https://user-images.githubusercontent.com/88408350/144511149-2f3483fe-98fe-49d4-8bc4-5692a160d525.png">


**- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?**

Percentage of Vine reviews were 5 stars: 

<img width="617" alt="Screen Shot 2021-12-02 at 2 10 05 PM" src="https://user-images.githubusercontent.com/88408350/144511262-c147b49f-f19f-4982-a351-1d17c4a55931.png">


Percentage of non-Vine reviews were 5 stars:

<img width="700" alt="Screen Shot 2021-12-02 at 2 09 56 PM" src="https://user-images.githubusercontent.com/88408350/144511246-bda59ec9-0d10-447d-85ff-fcbb4c2d84b0.png">

## Summary:
Positivity bias is a general preference shown by most people for positive relations. Since about 51% of Vine reviews received 5 stars and about 38% of non-Vine reviews received 5 stars, there is some positivity bias.

Some additional analysis I would add are the 3 main types of descriptive statistics which are the frequency distribution, central tendency, and variability of a dataset. By doing this, we can determine more clearly and accurately to see if our results change. 

Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews

# Amazon Vine Analysis

# Overview:

In this project, I have access to approximately 50 datasets, where I will be choosing one data set “Home Entertainment”, which contains reviews of a specific product. I will use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then, I will use PySpark and Pandas to determine if there is any bias toward favorable reviews from Vine members in your dataset. After the analysis, will write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

# Results:
 
•	The total vine and non-vine reviews were 261 and 24,040.
•	The total 5-star ratings for vine or non-vine reviews were 106 and 10,899.
•	The percentage for vine and non-vine 5-star ratings were 40.61% and 45.34%.

# Summary:

In Amazon Vine Reviews, we determined the paid and unpaid 5-start reviews and their percentage. The results for vine and non-vine reviews shows positivity bias.
The results of Vine paid reviews, the total no’s 261 and 5-star ratings 106. The percentage of the paid vine reviews is 41% approx. The results for non-vine reviews, total reviews were 20,040 and 5-star rating was 10,899. And the percentage of unpaid vine reviews is 45%.

If we start comparing the percentage results of paid and unpaid vine reviews, we will see that its only 4% difference between them. The 5-star paid vine reviews percentage 41% approx. shows the positivity in the trend that it can even out the 5-star unpaid reviews. 

To support the positivity bias, I would perform the analysis on review_ID, which can show how many people participated in the writing reviews (paid or un-paid) and how many times they wrote a positive or negative review.

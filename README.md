# Amazon_Vine_Analysis
# Overview of the analysis: Explain the purpose of this analysis.
This project was working with Sellby, an online e-commerce company.  We were to analyze their reviews written by customers who paid to write a review.  This program was called Amazin Vine, a service that allows companies to seed products to customers for free and in return they would write a review. 

For this project, we decided to review camera dataset, using PySpark to perform an ETL process.  Then we used Jupyter notebook to analyze the dataset. 

# Results: Using bulleted lists and images of DataFrames as support, address the following questions:

* How many Vine reviews and non-Vine reviews were there?
    * 607 Vine Customers
    * 50,522 Non-Vine Customers 

![image](https://github.com/icheung487/Amazon_Vine_Analysis/blob/main/Resources/Total_Number_of_Vine.png)


* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
There was 257 Vine customers vs. 25,220 organic customers that rated gave a 5 stars.  There could be many variables but it's clear that organically this does well. 


![image](https://github.com/icheung487/Amazon_Vine_Analysis/blob/main/Resources/Total_Number_with_5_Stars.png)

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

As shown below, 42% of the reviews were from Vine reviews and 49% non-vine reviews.  It was close to even but there was slightly more organic reviews. 

![image](https://github.com/icheung487/Amazon_Vine_Analysis/blob/main/Resources/Percentage_Vine_reviews.png)


# Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
The results from the analysis indicated there was not bias to the Vine program.  There was slightly more organic reviews(49%) giving camera products a 5-star vs. Vine customers(42%).  

Another dataset we can look into is the helpful_vote to better understand how many customers thought the comments were helpful.  We can analyze how many customers thought the comments were helpful between VINE and Non-vine.  This would help support if there was any bias between the two or demonstrate possible outliers in the overall dataset.  

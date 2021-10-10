# Amazon_Vine_Analysis
## Overview of the analysis 
In this challenge, we have to analyze Amazon reviews written by members of the paid Amazon Vine program and find whether the results are biased or not. 

Using knowledge of the cloud ETL process, I have created an AWS RDS database named ‘AWS’ with tables in pgAdmin.
Then chose a dataset from the Amazon Review datasets , and extracted the dataset into a DataFrame. I transformed the DataFrame into four separate DataFrames that match the table schema in pgAdmin. Then, uploaded the transformed data into the customer_table,products_table,review_id_table,vine_table and run queries in pgAdmin to confirm that the data has been uploaded. In google colab, I calculated the required percentage to confirm whether the review matches for both vine paid and unpaid members.

I have used Google colab,PGAdmin,Aws for this challenge.

### Results:
CUSTOMERS_TABLE


![png_chmd167](https://github.com/Ruma-T/Amazon_Vine_Analysis/blob/main/resources/chmd16p7.PNG)





 
 
PRODUCTS_TABLE

![png_chmod16p2](https://github.com/Ruma-T/Amazon_Vine_Analysis/blob/main/resources/chmod16p2.PNG)




REVIEW_ID_TABLE

![png_chmod16p4](https://github.com/Ruma-T/Amazon_Vine_Analysis/blob/main/resources/chmod16p4.PNG)





VINE_ANALYSIS_RESULTS

![png_ch16p1](https://github.com/Ruma-T/Amazon_Vine_Analysis/blob/main/resources/ch16p1.PNG)



![png_Chmod16p6](https://github.com/Ruma-T/Amazon_Vine_Analysis/blob/main/resources/Chmod16p6.PNG)



![png_Chmod16p10](https://github.com/Ruma-T/Amazon_Vine_Analysis/blob/main/resources/Chmod16p10.PNG)



![png_Chmod16p11](https://github.com/Ruma-T/Amazon_Vine_Analysis/blob/main/resources/Chmod16p11.PNG)





![png_Chmod16p12](https://github.com/Ruma-T/Amazon_Vine_Analysis/blob/main/resources/Chmod16p12.PNG)





![png_Chmod16p13](https://github.com/Ruma-T/Amazon_Vine_Analysis/blob/main/resources/Chmod16p13.PNG)






![png_Chmod16p9](https://github.com/Ruma-T/Amazon_Vine_Analysis/blob/main/resources/Chmod16p9.PNG)





![png_chmod16p8](https://github.com/Ruma-T/Amazon_Vine_Analysis/blob/main/resources/chmod16p8.PNG)


### Summary:
### Total Vine reviews :463  
### non-Vine reviews were there:25094

### Vine reviews were 5 stars:202
### non-Vine reviews were 5 stars:12033
### percentage of Vine reviews were 5 stars :44%
### percentage of non-Vine reviews were 5 stars: 48%
So, the percentage of vine paid and nonvine unpaid members five star review shows that it is not biased. The five star review percentage is close.

We can also check how low reviews are given by paid and unpaid vine members.

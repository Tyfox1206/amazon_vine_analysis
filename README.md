# amazon_vine_analysis
## Overview of the Analysis 
for deliverable 1 I took a large data dump provided by amazon and transformed the data and then worked with uploading it into an AWS RDS that can be accessed with pgadmin. I uploaded for tables into the AWS RDS, the tables are customers_table, products_table, review_id_table, and vine_table. below are images of each of the tables showing in pgadmin with populated data. 

![customers_table](https://github.com/Tyfox1206/amazon_vine_analysis/blob/main/images/customer_table.PNG) ![products_table](https://github.com/Tyfox1206/amazon_vine_analysis/blob/main/images/products_table.PNG)

![review_id_table](https://github.com/Tyfox1206/amazon_vine_analysis/blob/main/images/review_id_table.PNG) ![vine_table](https://github.com/Tyfox1206/amazon_vine_analysis/blob/main/images/vine_table.PNG)

## Results

* With the data I selected there were no paid reviews for any of the amazon products. So I am not able to provide a precentage of paid reviews to five star rating.
*  For the non paid reviews there were a total of 1685 reviews and 631 five star reviews. This means that 37% of the reviewers gave the products a five star review. 
    * I was only tracking the products that had more then 20 total votes and where more tehn 50% of people found those votes helpful. 

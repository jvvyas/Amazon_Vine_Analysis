# Amazon_Vine_Analysis
Analyzing Amazon Vine  Reviews using PySpark &amp; AWS

## Project Overview 

The  Project is about Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. There are several companies who pays a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. To execute this project we have an access to approximately 50 datasets to choose from a specific product, from clothing apparel to wireless products. And so we picked the dataset of clothing apparel and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. We used Pandas, to determine if there is any bias toward favorable reviews from Vine members in our dataset. 


## Resources

- Technologies used:Google Colab to run PySpark, Jupyter Notebook, PostreSQL/pgAdmin & tools of Amazon Web Services

- Datasets : Amazon Review Datasets & CSV file

## Creating DataFrames :

- Customers_Table

![Customers_ID](https://user-images.githubusercontent.com/93893263/173032970-2117a4aa-63b0-4808-b7ca-65abc8aed59c.png)


- Product_Table 

![Product_ID](https://user-images.githubusercontent.com/93893263/173033089-3b5588c2-7a4a-431d-9e9b-420b00ce3ff1.png)


- Review_ID_Table 

![Review_ID](https://user-images.githubusercontent.com/93893263/173033172-3d3375ef-3184-4913-9da4-2884410d2272.png)


- Vine_Table

![Vine_Table](https://user-images.githubusercontent.com/93893263/173033258-c4d80a95-f623-40f6-8ed6-bd14703d36c9.png)


## Project Result :

![image](https://user-images.githubusercontent.com/93893263/173036061-82eafc98-08d1-4bc0-b141-116bfa0a65e2.png)


## Project Summary:

Unfortunately Clothing Apparel catagory is not strong to run a vine program to determine the anticipated results. Its not even worth to pay customers and induced them to write better reviews, instead consider the organic reviews. 

![Average_StarRatings](https://user-images.githubusercontent.com/93893263/173038617-bc7ce296-618e-4cf3-8c7a-924fdc5a2400.png)


In fact, there is a slight difference in the average star rating of both paid and organic reviews and not worth conducting a vine program at the first place, unless we consider more data and deploy Machine Learning methods. 



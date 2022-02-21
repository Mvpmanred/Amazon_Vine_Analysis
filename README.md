# Amazon_Vine_Analysis

## Overview of the analysis of the Vine program:
In this project, I will have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. I will need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I will use PySpark if there is any bias toward favorable reviews from Vine members in the dataset. Then, I will write a summary of the analysis for Jennifer to submit to the SellBy stakeholders. I will be using this dataset https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Electronics_v1_00.tsv.gz to perform my analysis.

## Results
![Capture4](https://user-images.githubusercontent.com/92561493/155034482-733fc8e3-e79a-44a8-98c5-c50a3a161256.PNG)
- Total number of reviews for vine members is 1080
- Total number of reviews for nonvine is 49673
- Total number of reviews for nonvine is 50753
![Capture3](https://user-images.githubusercontent.com/92561493/155034610-3b5ff1c2-b34f-4396-8b1e-a6b3604e82a8.PNG)
![Capture5](https://user-images.githubusercontent.com/92561493/155034727-76a4c01c-d01b-4e79-8790-2a86779ce266.PNG)

- Total nonvine members with five stars is 23043
- Total vine members with five stars is 454
- Total review with five stars is 23497 

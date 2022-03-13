# Cryptocurrencies

## Overview 
The purpose of this project is to assist my client in offering a new cryptocurrency investment portfolio for its customers using Machine Learning (ML).  My client; however, is lost in the vast universe of cryptocurrencies. So, they’ve me to assist with creating a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

The data my client is working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what my client is looking for, they have decided to use unsupervised learning. To group the cryptocurrencies, they decided on a clustering algorithm. I will assist with creating data visualizations to share my findings with the board.  As always, my analysis followed the data analysis principles of (1) Determine the number of rows and columns; (2) Data types used; and (3) Is the data readable?

__Client Deliverables:__
- Deliverable 1: Preprocessing the Data for PCA
- Deliverable 2: Reducing Data Dimensions Using PCA
- Deliverable 3: Clustering Cryptocurrencies Using K-means
- Deliverable 4: Visualizing Cryptocurrencies Results

## Resources
The resouces used for this analysis included;
- Visual Studio Code
- Python
- Unsupervised Machine Learning

## Results
All sprints were completed as scheduled and I delivered on all client expectations/results. The below images  will visualize the expected client results.

### Deliverable 1: Preprocessing the Data for PCA

This deliverable required me to create a new database with Amazon RDS (Relational Database Service) and add database tables and data to this database using pgADMIN.  The data was successfully loaded using my PySpark ETL pipleline.

![](https://github.com/SheaButta/Amazon_Vine_Analysis/blob/main/Images/customer.PNG)


### Deliverable 2: Reducing Data Dimensions Using PCA

This deliverable required me to collect and manipulate the dataset to generate various calculations which will help determine bias of vine review.  The various calculated parts are identified below to help determine the possibility of bias of Vine Reviews.

   _**Percentage of non-Vine reviews were 5 stars**_
   
   ![](https://github.com/SheaButta/Amazon_Vine_Analysis/blob/main/Images/Percent_UNPAID_5Star.PNG)


### Deliverable 3: Clustering Cryptocurrencies Using K-means

This deliverable required me to collect and manipulate the dataset to generate various calculations which will help determine bias of vine review.  The various calculated parts are identified below to help determine the possibility of bias of Vine Reviews.

   _**Percentage of non-Vine reviews were 5 stars**_
   
   ![](https://github.com/SheaButta/Amazon_Vine_Analysis/blob/main/Images/Percent_UNPAID_5Star.PNG)
   

### Deliverable 4: Visualizing Cryptocurrencies Results

This deliverable required me to collect and manipulate the dataset to generate various calculations which will help determine bias of vine review.  The various calculated parts are identified below to help determine the possibility of bias of Vine Reviews.

   _**Percentage of non-Vine reviews were 5 stars**_
   
   ![](https://github.com/SheaButta/Amazon_Vine_Analysis/blob/main/Images/Percent_UNPAID_5Star.PNG)


   
## Summary
The review of the data appears to show some bias in the Vine program for the non-Vine 5-Star reviews.  Although the percentage of bias is not even 50%, 47% is stil relatively close.  Some additional analysis to capture mean, median and mode of the Vine and non-Vine reviews would help quantify this review.
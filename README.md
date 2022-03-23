# Amazon_vine_analysis

## Overview
The purpose of our analysis is to analyze the reviews of a product similar to our clients product on Amazon, in order to help them in creating a marketing strategy for their product. 
In this analysis we have used Pyspark to extract data from an external data source. Used Goggle Collab to create dataframes for the extracted Data as well as Dataframes for the reviews. Created a data storage file on AWS using RDS on Postgresql.

## Summary
#### Extracted Data converted into DataFrames
<img width="1440" alt="Screen Shot 2022-03-22 at 10 23 09 PM" src="https://user-images.githubusercontent.com/91028094/159613830-b59dfc7a-a404-4dd5-ab01-59508529ea2c.png">


<img width="1440" alt="Screen Shot 2022-03-22 at 10 23 13 PM" src="https://user-images.githubusercontent.com/91028094/159613828-a3cd93b7-5219-46db-aa95-e39672de530f.png">
<img width="1440" alt="Screen Shot 2022-03-22 at 10 23 16 PM" src="https://user-images.githubusercontent.com/91028094/159613825-4fcddd82-92bc-4276-9868-6be12d8df58a.png">
<img width="1440" alt="Screen Shot 2022-03-22 at 10 23 23 PM" src="https://user-images.githubusercontent.com/91028094/159613820-62f2325b-61ce-4b29-9880-8bd21071dd96.png">
<img width="1440" alt="Screen Shot 2022-03-22 at 10 23 26 PM" src="https://user-images.githubusercontent.com/91028094/159613816-07bf9a56-b117-42bb-b023-04af702c80b0.png">

#### Here is the Database created with the help of RDS and Postgresql
<img width="1440" alt="Screen Shot 2022-03-23 at 7 07 06 PM" src="https://user-images.githubusercontent.com/91028094/159812385-3628eb37-b14e-4fe0-80ac-31aa36b56faf.png">

# Results

<img width="1440" alt="Screen Shot 2022-03-23 at 7 25 24 PM" src="https://user-images.githubusercontent.com/91028094/159812733-b92e5690-9b45-40df-ba39-4f6e16bb7d77.png">

- Total Vine reviews : 94
- Total non-Vine reviews : 40471
- 5 start vine reviews : 48
- 5 start non-vine reviews : 15663
- 5 star vine % : 5 star non-vine % == 51.06 : 38.70

## Opinion
As I look at the results, I cn=an say I don't recognise any bias among paid and unpaid 5 strat reviews meaning I can't see any corelation among the reviews if paid reviews had more 5 stars rather than unpaid ones.

Another thing is that we can include more reviews other than only 5 stars meaning we can get more results that will be influential if we include the 1 star reviews, It can help in deciding the variance among the reviews as well as helps in identifying non-popular products.

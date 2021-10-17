# Movies-ETL

## Overview:
This analysis aims to create an extract, transform, load (ETL) pipeline for combining information from two different data sets, Wikipedia and Kaggle.

## Results

This ETL pipeline results in two tables in our SQL database. ```Movies```includes a cleaned Wikipedia and Kaggle metadata datasets and a ```Results``` table that includes information from Kaggle. Results were as follows:
- ![Movies query](https://github.com/HappyM0f0/Movies-ETL/blob/main/Resources/movies_query.png)
- Movies table has 6,075 entries
- ![Ratings query](https://github.com/HappyM0f0/Movies-ETL/blob/main/Resources/ratings_query.png)
- Ratings table has 26,024,289 entries
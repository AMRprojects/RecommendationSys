# RecommendationSys
This repository contains the in-progress effort to build a recommender system using the movielens dataset.  
Planning to swap datasets to expand the project – I don’t know much about movies, so it is difficult to get an intuitive sense of how the system is working. Need to find a data set that I have more experience with, to be able to discern effectiveness while practicing  
After swapping dataset, planning to implement Content-based filter (and rebuild a collaborative filter) and then combine the two into a hybrid system.  

***Collaborative Filter***   
Work performed on the movielens 1M dataset  
Analysis performed in Databricks using Apache Spark – pyspark and spark SQL  
Collaborative filter uses similarities between users and items simultaneously to provide recommendations. Movielens set contains explicit movie ratings. Algorithm provided in FILE utilizes Alternating Least Squares (ALS) algorithm to factorize user/item matrix.  
  
References:  
https://www.nvidia.com/en-us/glossary/recommendation-system/  
https://developers.google.com/machine-learning/recommendation/content-based/basics  
https://nightlies.apache.org/flink/flink-docs-release-1.4/dev/libs/ml/als.html  

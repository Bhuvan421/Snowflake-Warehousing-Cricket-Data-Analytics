# Snowflake-Warehousing-Cricket-Data-Warehousing-Analytics

This is an end to end Data Engineering project using snowflake cloud datawarehouse to preprocess and transform the deeply nested unstructured data into a clean structured data, perform data analysis and visualization and create a final dashboard with key indicators. 
The data is about the game called "CRICKET" (Yes, there is a very popular and much entertaining game called cricket, its not an insect! for those that do not know.😊) 

The data is highly unstructured with about 10 times flattening the data brings us the child of the root attribute.  
Here is the sample data hierarchy of data (each of these nodes have different levels of children)

![Alt text](https://github.com/Bhuvan421/Snowflake-Warehousing-Cricket-Data-Analytics/blob/efc537f874cfc292cc6c930d56f27f917aeab1f4/sample-data-hierarchy.png)


#### Work done in the project:
1. Load the data from external stage (S3) into snowflake (using SnowSQL) - extract stage
2. Copied the staging data into respective raw transient tables - raw stage
3. Preprocessed, cleaned and transformed data into silver layer tables - clean aggregated stage
4. As per needs, fetched, transformed, and aggregated necessary data into gold staging tables - clean aggregated stage
5. Designed and implemented data modelling following all dimentional modelling rules and designed fact and dimention tables - loading stage
6. Automated the entire data pipeline using tasks and streams - automation stage
7. Connected to an external visualization/dashboarding tool Tableau. (Can be done inside snowflake as well) -- visualize and strategy/decision making stage

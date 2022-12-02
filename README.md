# Crowdfunding ETL

## Extract Data

### The first step in our analysis was to extract the data. The original data structure was not sustainable and in order to progress, we needed to clean it. In doing so, we were able to clean the data with Python for further in depth analysis.

## Transforming Data

### Similar to the extract stage, we needed to clean the data into a more suitable format. This was done by splitting columns and adjusting column data types. The final result of the transforming phase was the [backers data](https://github.com/Ctblossey/Crowdfunding-ETL/blob/main/Files/backers.csv).

## ERD and Table Schema

### When writing in SQL it is very important to develop an ERD (shown below). After doing so, we were able to begin our analysis. We took our base data files and imported the data into the tables we had created. This allows us to draw out analysis and relationships between the tables.

### ![ERD](https://github.com/Ctblossey/Crowdfunding-ETL/blob/main/ERD/crowdfunding_db_relationships.png)

## SQL Analysis

### Our final analysis consisted of four main exercises: backer counts for each cf_id, confirming the previous results with a different table, creating and exporting an [email contacts file](https://github.com/Ctblossey/Crowdfunding-ETL/blob/main/Files/email_contacts_remaining_goal_amount.csv), and creating and exporting an [email backers file](https://github.com/Ctblossey/Crowdfunding-ETL/blob/main/Files/email_backers_remaining_goal_amount.csv).
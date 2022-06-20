# Module 8 Challenge - Movies-ETL

## Overview of Project

### Purpose

The purpose of this project is to build a program capable of performing a full ETL process automatically. Our program is capable of reading both CSV and JSON files from Wikipedia, Kaggle, and MovieLens. The program then proceeds to cleaning and transforming various numeric and string columns before merging all three files into a single dataset. Finally, the program creates a new SQL database and stores the merged dataset in the new database for analysis at Amazing Prime's Hackathon event.

## Summary

Once the program is run, we can use SQL queries in PgAdmin to confirm the merged dataset's integrity. A query of the ratings_challenge table returns 26,024,289 rows while a query of the movies_challenge table returns 6,052 rows.
![movies_query](https://user-images.githubusercontent.com/103288980/174516472-f13a9f9d-b9a8-4367-a50a-978ed484db86.PNG)
![ratings_query](https://user-images.githubusercontent.com/103288980/174516481-5f0914e4-c1f3-4f49-90b0-bd77fea269b5.PNG)

# ETL-Project
This project executes a fundamental Extract, Transform, Load (ETL) process utilizing SQL and Python. Flight delay data from 2015, sourced from Kaggle's dataset repository, was utilized for analysis.

The workflow includes the following steps:

1. Uploading Excel sheets into a SQL Lite database.
2. Performing data transformation using SQL Alchemy in Python, including executing queries and joins, data is rolled up to the desired grain.
3. Leveraging the transformed data in Python for further analysis, which involved performing calculations and adding additional columns using pandas.
4. Directly uploading the analysis results from Python back into the SQLite database.
5. Additionally, transformed tables were exported into MySQL to accommodate user preferences for database management systems.



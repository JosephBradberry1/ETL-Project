# Global Wealth ETL Project
## Objective:
This project demonstrates my skills in data engineering, particularly in the Extract, Transform, and Load (ETL) processes, using Python and PostgreSQL. It's designed to showcase my abilities in handling, cleaning, and storing datasets.
## Project Overview
### Data Source:
The project utilized global wealth data, encompassing various economic indicators and country-specific financial information from databank.worldbank.org
### Data Importing:
Data was imported into Python using the Pandas library.
### Data Cleaning:
In Python, I performed data cleaning operations to refine the dataset. This step involved selecting relevant columns and preparing the data for database insertion.
### Database Model Creation: 
Before loading the data into the database, I designed a database model to effectively organize and store the data.
### Database Creation: 
Using Python's psycopg2 library to interact with PostgreSQL, I created a database named 'accounts'. This process included establishing connections and executing SQL commands to set up the database environment.
### Data Loading: 
The cleaned data was then loaded into the SQL database. Data insertion into the database was performed using looped execution of SQL INSERT commands, ensuring efficient and accurate data transfer.

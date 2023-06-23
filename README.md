# Crowdfunding Data ETL Project

## Team: Ji Ran,	Gorvie Alfred 

This repository hosts the codebase for the Crowdfunding Data ETL project. This project is designed to extract, transform, and load crowdfunding data into a structured database format using Python, Pandas, and PostgreSQL.  

## About The Project 
The Crowdfunding Data ETL project is a comprehensive pipeline that takes raw data from multiple sources, transforms it into a usable format, and loads it into a PostgreSQL database. The aim of the project is to convert disorganized data into a structured format, making it easier for end-users to analyze and glean insights. 

The primary steps involved in this project are:  

Extracting data from the source files  
Transforming and cleaning the data  
Creating four CSV files: Category, Subcategory, Campaign, Contacts  
Creating an Entity Relationship Diagram (ERD) and a table schema  
Loading the CSV data into a PostgreSQL database  

## Tech Stack
Python: Programming language used for building the ETL pipeline  
Pandas: Data analysis and manipulation tool  
PostgreSQL: Open-source relational database used for data storage  
Regular Expressions and Python Dictionary Methods: Used for data extraction and transformation  

## Installation & Usage 
1. Clone the Repository
2. Run the jupyter notebook file "ETL_Mini_Project_JRan_AGorvie.ipynb", to get the 4 CSV files(which are already in the Resources folder)
3. Run PostgreSQL, build a database named 'crowdfunding_db'
4. Run the schema file "crowdfunding_db_schema.sql" to build the tables.
5. Import CSV files to tables one by one. note: follow the order "crowdfunding_db_dbd.png" shows to avoid error.

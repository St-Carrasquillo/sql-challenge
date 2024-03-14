# sql-challenge

## Data Modeling
Used the provided website QuickDBD.com to create the ERD. 
- Schema shared
- Image of diagram provided

## Data Engineering
To create the tables:
- I mostly used the VARCHAR data type
- Used INTEGER for the emp_no since they were all numerical
- All tables (except for 2) had a singular primary key
- Because of duplication in all columns, dept_emp and dept_manager tables needed composite key, both columns were used as primary key
- Initially had a challenge importing data from CSV files but I realized they needed to be imported in a specific order. 
- Imported the employees.csv data first then the other tables.

## Data Analysis
I created all the analysis queries in a single file and tested all, ensuring results were accurate. 

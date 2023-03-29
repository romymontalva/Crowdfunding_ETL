# Crowdfunding_ETL
ETL mini project
I worked in this project using ETL, Python and Pandas.
After I transformed the data, I created four CSV files and use the CSV file data to create an ERD and a table schema. Finally, I uploaded the CSV file data into a Postgres database.
Find the steps I followed below:

I extracted and transformed the crowdfunding.xlsx Excel data to create 4 data frames: Category, Subcategory, Campaign and Contacts with the requested columns.
Then, I Inspected the four CSV files, and then sketched an ERD of the tables by using QuickDBD.
I used the information from the ERD to create a table schema for each CSV file. After that I created a new Postgres database, where using the database schema, I created the tables in the correct order to handle the foreign keys.
I imported each CSV file into its corresponding SQL table. 

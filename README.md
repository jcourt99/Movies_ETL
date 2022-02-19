# Movies_ETL
Module 8 - ETL

# Overview
This challenge uses data from three websites: Wikipedia, Kaggle, and MovieLens. The Extract-Transform_Load (ETL) process is used to create a meaningful SQL database of movie data for the customer, Amazing Prime.

# Deliverables
There are 4 technical analysis deliverables required for this assignment:

* Deliverable 1 - Write an ETL Function to read the 3 data files
* Deliverable 2 - Extract and Transform the Wikipedia data
* Deliverable 3 - Extract and Transform the Kaggle data
* Deliverable 4 - Create the Movie Database

# Results
A function was written to allow the customer to update the data from the 3 sources on a daily basis. 
After extracting the data from the 3 sources, further analysis was completed to determine the best way to clean the data. The transformation of the data involved removing null values, deleting duplicate data and columns, removing less relevant information, and renaming the columns. The merged datasets were then loaded to a SQL database which allows the customer to query and generate reports on the data.

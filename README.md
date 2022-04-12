![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

# Copy data from csv file to database


### PREREQUISITES:

> NOTE: Here we are using postgres database. But most of the code gonna be same in case we haev to use any other database.
> But we have to make sure, we need replace SQL related scripts and database connection string based on database we have to use

1. Download & install postgres database from https://www.postgresql.org/download/
2. Download pgadmin4 from https://www.pgadmin.org/download/ or any other postgres client

### USE CASES

#### 1. COPY DATA FROM CSV to DATABASE (via Pandas Dataframe)

_https://github.com/me-rsharma/py-csv-db/blob/main/notebooks/001-ImportCSVtoDfToDatabase.ipynb_

  - Here, we have to copy data from CSV file to postgres database.  
  - Firstly, we are converting data from csv to pandas dataframe  
  - Then we are cleaning the columns name and generate table name and table columns  
  - Creating table using file name  
  - Naming table columns from dataframe columns  
  - Finally. moving data from dataframe to database  

#### 2. COPY DATA FROM CSV to DATABASE

_https://github.com/me-rsharma/py-csv-db/blob/main/notebooks/002-ImportCSVToDatabaseAutomate.ipynb_

  - Here, we have to copy data from CSV file to postgres database.  
  - Firstly, we are converting data from csv to pandas dataframe  
  - Then we are cleaning the columns name and generate table name and table columns  
  - Creating table using file name  
  - Naming table columns from dataframe columns
  - After cleaning data usning pandas df, we need to export df data to csv file  
  - Finally. copying data from csv to database  


#### 3. COPY DATA FROM MULTIPLE CSV to DATABASE TABLES (AUTOMATE)

_https://github.com/me-rsharma/py-csv-db/blob/main/notebooks/003-CopyCSVDataToDatabaseAutomate.ipynb_

  - Here, we have to copy data from multiple CSV file to postgres database.  
  - Also, we have modified our code in such a way that n no. of files can be uploaded to n number of database w/o - making any change to code  
  - Firstly, we are converting data from csv to pandas dataframe  
  - Then we are cleaning the columns name and generate table name and table columns  
  - Creating table using file name  
  - Naming table columns from dataframe columns  
  - After cleaning data usning pandas df, we need to export df data to csv file  
  - Finally. copying data from csv to database



# Snowflake-TT-FF
repo holds the data files to define snowflake time travel and fail safe features .

QUERY -->  AT (timestamp,offset)  / BEFORE(statement)  

URL - https://docs.snowflake.com/en/user-guide/data-time-travel.html

We can use this feature in 3 ways
  
  1.Query the hisorical data (DDL/DML) done on tables ,schemas,databases.
  
  2.Creation of backup schemas/databases/tables using CLONE feature AT/BEFORE a particular time.
  
  3.UNDROP the tables/Schemas/Databases.

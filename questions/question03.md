# Question

source: <http://cca175cloudera.training4exam.com/module-3-1>

Problem Scenerio 3: You have been given MySQL DB with following details.
user=retail_dba
password=cloudera
database=retail_db
table=retail_db.categories
jdbc URL = jdbc:mysql://quickstart:3306/retail_db
Please accomplish following activities.
1. Import data from catagories table, where catagory=22 (Data should be stored in categories_subset)
2. Import data from catagories table, where catagory>22 (Data should be stored in categories_subset_2)
3. Import data from catagories table, where catagory  between 1 and 22 (Data should be stored in categories_subset_3)
4. While importing catagories data change the delimiter to '|' (Data should be stored in categories_subset_6)
5. Importing data from catagories table and restrict the import to category_name,category_id columns only with delimiter as  '|'
6. Add null values in the table using below SQL statement
ALTER TABLE categories modify category_department_id int(11);
INSERT INTO categories values (60,NULL,'TESTING');
7. Importing data from catagories table (In categories_subset_17 directory) using '|' delimiter and category_id between 1 and 61
 and encode null values for both string and non string columns.
 8. Import entire schema retail_db in a directory categories_subset_all_tables

## Answer

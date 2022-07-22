##Schema design and information on your tables: 
What is the fact table? 
=> table songplays

And what are the dimension tables?
=> table users,songs,artists,time

##Instruction on how to run the Python scripts.

step 1. run create_tables.py reset data, for drop table and create table
step 2. menu File > terminal , type : python etl.py



##Explanation of the files in the repository.
1. sql_queries.py : create query list (create_table_queries, drop_table_queries )

2. create_table.py will import the query list above

3. etl.ipynb : build and check python code step by step

4. etl.py : run the final etl scripts.


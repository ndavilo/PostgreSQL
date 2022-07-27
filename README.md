# PostgreSQL
PostgreSQL note
PostgreSQL

Database: is a computer server where you can store, manipulate and retrieve data.

Postgres is the database engine, where SQL is Structured Query Language.
Data are stored in tables, which are made up of columns and rows. The tables are named and the columns are also named, rows are mostly represented by an id.  For example:
Table named coins has the following columns:
['id', 'bitcoin_value', 'etherem_value', 'tether_value', 'binance_value',
       'date_time']

and Rows:
	id	bitcoin_value	etherem_value	tether_value	binance_value	date_time
0	1	29681.9264	1767.9025	0.9991	1.0003	2022-06-04 13:04:07.945000+00:00
1	2	29681.9264	1767.9025	0.9991	1.0003	2022-06-04 13:04:16.774000+00:00

Relational database: SQL allows us to relate two or more data base or tables
Tables are related by the use of ids. Example:
Table1 named: post
  id	title	                  body	                                  date_time	            	     author_id
1	Disclaimer	The Site Does Not Guarantee That The Sites Wil...	2022-06-07 09:45:45.596102+00:00		    1

Table2 named: user
id	password	last_login	                      username	        email
1	$Xj...	2022-06-04 12:59:54.037000+00:00	chukwunonsodavid	nonsoilonze@gmail.com

The author_id in Table 1 is related to Table 2 by the id number 1.


SQL Joins: are statements used to combine data or rows from two or more tables based on a common field between them.

Types of SQL joins: Inner Join, Left Join, Right Join, Full Join. 

Inner Join: returns those records which have matching values in both tables. FROM table1 INNER JOIN table2.

Left Join: returns all the records from the left table and also those records which satisfy a condition from the right table. FROM table1 LEFT JOIN table2

Right Join: returns all the records from the right table and also those records which satisfy a condition from the left table. FROM table1 RIGHT JOIN table2

Full Join: returns all the rows from both the tables. FROM table1 LEFT JOIN table2


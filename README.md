# SQL Basics 
# SQL Grasshopper: Select Columns
kata link: http://www.codewars.com/kata/sql-grasshopper-select-columns/train/sql

Solution link: http://www.codewars.com/kata/582365c18917435ab3000020/solutions/sql

Discussion link: http://www.codewars.com/kata/sql-grasshopper-select-columns/discuss/sql

Instructions: 
#Greetings Grasshopper!# Using only SQL, write a query that returns all rows in the custid, custname, and custstate columns from the customers table.

###Table Description for customers:###

Column	    Data Type	        Size	        Sample
custid	    integer	           8	          4
custname	  string	           50	          Anakin Skywalker
custstate	  string	           50	          Tatooine
custard	    string	           50	          R2-D2


# Solution: 
SELECT CUSTID,CUSTNAME,CUSTSTATE 
FROM CUSTOMERS;

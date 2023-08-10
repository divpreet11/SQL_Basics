# SQL_Basics

# Assignment-1

Calculate the average price of products sold.

product_id | price
-------------- | -------

1      | 10.00

2      | 15.50

3      | 8.75

4      | 20.25

5      | 12.00

# Queries:
1. create database learningsql
2. use learningsql;
3. create table ProductDetails(product_id int primary key auto_increment, price float(2));
4. insert into ProductDetails(price) value(10.00),(15.50),(8.75),(20.25),(12.00);
5. select *from ProductDetails;
6. select AVG(price) from ProductDetails;

**************************************************************************************************************************

# Assignment -2 

Retrieve all the books from the table and display their titles, authors, and published years.


| Title        | Author       | Published Year |

|------------------------|---------------------|----------------|

| Harry Potter    | J.K. Rowling    | 1997      |

| The Great Gatsby  | F. Scott Fitzgerald | 1925      |

| To Kill a Mockingbird | Harper Lee     | 1960      |

# Queries:
1. use learningsql;
2. create table Books(Title varchar(50), Author varchar(25), Published_Year int);
3. insert into Books values('Harry Potter','J.K. Rowling',1997),('The Great Gatsby','F. Scott Fitzgerald',1925),('To kill a Mockingbird','Harper Lee',1960);
4. select *from Books;

# DMDD

DMDD NOTES 

Reference video shared by Professor:

SQL Basics for Beginners | Learn SQL | SQL Tutorial for Beginners | Edureka
https://www.youtube.com/watch?v=BPHAr4QGGVE


Table in database: 
Table in a database is a collection of data that is organized into rows and columns. Tables are used to store data in an organized manner and make it easier to find and retrieve specific data. Each table can have multiple columns and rows which can hold various types of data.


CREATE:
The CREATE TABLE statement is used to create a new table in a database.
Example CREATE TABLE Persons (
    PersonID int PRIMARY KEY,
    LastName varchar(255),
    FirstName varchar(255),
    Address varchar(255),
    City varchar(255)
);

INSERT:
The INSERT INTO statement is used to insert new records in a table.
Example: INSERT INTO Customers (CustomerName, ContactName, Address, City, PostalCode, Country)
VALUES ('Cardinal', 'Tom B. Erichsen', 'Skagen 21', 'Stavanger', '4006', 'Norway');
 Inserts a new record in the "Customers" table:

UPDATE: 
The first customer (CustomerID = 1) is updated with a new city and contact person in the following SQL query.
Example: UPDATE Customers
SET ContactName = 'Alfred Schmidt', City= 'Frankfurt'
WHERE CustomerID = 1;



ALTER TABLE:
The ALTER TABLE statement is used to add, delete, or modify columns in an existing table.
ALTER TABLE table_name
ALTER COLUMN column_name datatype;

SEO keywords:
SEO keywords are also known as "search queries" in the context of SEO and refer to the words and phrases that users type into search engines. On every page of your website, use unique keywords in the places where bots and people typically go to reassure them that you have what they're looking for. This brings up a crucial point: the dangers of clickbait. This applies to both the title tag and the body of your material.


URLstatus codes:
URL status codes are the numerical codes that indicate the status of a request made to a URL. 
200 - This is your ideal status code for your normal, everyday, properly functioning page.
404 - This indicates that the server was unable to locate the file or page that the browser was requesting. 404 errors don't say if a page or resource is gone forever or just momentarily.
500 -   A 500 is a classic server error and will affect access to your site. 



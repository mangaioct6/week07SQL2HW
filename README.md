#### SQL AUTOINCREMENTING
Databases are known to store a large amount of data in a logical format.It’s practically impossible to enter the numbers manually. So, instead, we can use Auto Increment in SQL. Auto-increment allows a unique number to be generated automatically when a new record is inserted into a table. Often this is the primary key field that we would like to be created automatically every time a new record is inserted.

To use the auto increment field, in PostgreSQL, we have to create an auto-increment field with the sequence object. The sequence object generates a number sequence.

Syntax:

CREATE TABLE TableName (
Column1 DataType  SERIAL PRIMARY KEY,
Column2 DataType, 
);
#### FOR EXAMPLE:
Create a table with the name Customers, and columns CustomerID, CustomerName, Age and PhoneNumber. Auto-increment the CustomerID and make it the primary key for the table.

# APIs in C#

## In a SQL table, what is the difference between information in a row and information in a column?

* Information in a row represents an entire object in the table where as columns are specific elements of that object for instance. a row could represent a person but there might be a couple of columns in that row such as name age weight height ect. these are aspects or elements of the person row.

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

* CREATE TABLE characters(
  Id int NOT NULL,
  Name string,
  Age string,
  Description string
);

## What is the difference between the following statements: DELETE FROM table_name; DROP TABLE table_name;

* The first statement would delete something out of the table, but the table as a whole would still exist, where as the second statement would delete the entire table from you db. 

https://talanweeks.github.io/KnightsandCastles/

restarted knights relations entirely to do it better and add more data and populates

# DDL exercise 2
Creating Tables with Null and Not Null Constraints:
Create a table named Books with the following columns:

book_id (integer)
title (varchar, maximum length 100, not null)
author (varchar, maximum length 50)
genre (varchar, maximum length 50)
publish_date (date, not null)
Ensure that title and publish_date columns do not allow NULL values, while author and genre columns can have NULL values.

Altering Tables with Not Null Constraints:
Alter the Books table to modify the author column to not allow NULL values.

Dropping Tables:
Create a new table named Employees with the following columns:

employee_id (integer)
employee_name (varchar, maximum length 50, not null)
department (varchar, maximum length 50)
salary (decimal)
Then, drop the Employees table.

# DI_Bootcamp_week8_day4_Dailychallenge

Instructions
Create a simple stored procedure named add() that returns the product of two integers using plpgsql.

CREATE OR REPLACE FUNCTION add(
    a INTEGER,
    b INTEGER)
  RETURNS integer AS $$
BEGIN
return a + b;
END; $$
  LANGUAGE 'plpgsql';
Connect to the PostgreSQL database server by creating a new instance of the PDO class.

Prepare the statement that calls the stored procedure for execution using the prepare() method of the PDO object. The prepare() method returns a PDOStatement object.

Optionally pass values to the statement using the bindValue() method.

Execute the statement using the execute() method of the PDOStatement object.

You can pass the values to the statement when calling the execute() method as well.
Get the value using the fetchColumn() method that returns a single column of the next row in the result set.

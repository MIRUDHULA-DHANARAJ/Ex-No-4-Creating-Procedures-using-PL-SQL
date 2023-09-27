# Ex. No: 4 Creating Procedures using PL/SQL

### AIM:
To create a procedure using PL/SQL.

### Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create a procedure named as insert_employee data.
3. Inside the procdure block, write the query for inserting the values into the employee table.
4. End the procedure.
5. Call the insert_employee data procedure to insert the values into the employee table.
6. Display the employee table

### Program:
```
 CREATE TABLE empl(empid NUMBER,empname VARCHAR(10),dept VARCHAR(20),salary NUMBER);
 CREATE OR REPLACE PROCEDURE insert_empl_data AS
   BEGIN
   INSERT INTO empl(empid,empname,dept,salary)
   VALUES(1,'JOO','HR',100000);
   INSERT INTO empl(empid,empname,dept,salary)
   VALUES(2,'ANN','IT',20000);
   INSERT INTO empl(empid,empname,dept,salary)
   VALUES(3,'KEN','AP',30000);
   COMMIT;
   END;
    /
```

### Output:

![EXP-4](https://github.com/MIRUDHULA-DHANARAJ/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/94828147/91b5c210-5b17-4619-ae89-66ec49a0efdd)

### Result:
Thus a program To create a procedure using PL/SQL has been created successfully.


# DML-commands

Managers Table

This SQL script creates a table named Managers with the following fields : 

1. Manager_Id (Primary Key): Unique identifier for each manager.
2. First_name: Manager's first name.
3. Last_Name: Manager's last name.
4. DOB: Manager's date of birth.
5. Age: Manager's age (must be greater than 18).
6. Last_update: Timestamp when the record was last updated.
7. Gender: Manager's gender.
8. Department: Department the manager works in (e.g., 'IT', 'HR').
9. Salary: Manager's monthly salary (must not be NULL).
    
The table includes a CHECK constraint on Age to ensure the age is greater than 18, and the Salary field is marked NOT NULL.

Queries:
1. Insert 10 Rows:
   Ten rows of sample data are inserted into the Managers table, representing different managers from various departments.
2. Retrieve the Name and Date of Birth of the Manager with Manager_Id 1:
   A query is written to retrieve the first name, last name, and date of birth of the manager with Manager_Id = 1.
3. Display the Annual Income of All Managers:
   The query calculates the annual income for each manager by multiplying the monthly salary by 12.
4. Display All Managers Except 'Aaliya':
   A query is written to exclude the manager with the first name 'Aaliya' from the results.
5. Display Managers in 'IT' Department with Salary Greater Than 25000:
   A query is written to show managers from the 'IT' department who earn more than 25000 per month.
6. Display Managers with Salary Between 10000 and 35000:
   A query is written to display managers whose monthly salary lies between 10000 and 35000.
   
Conclusion:
This SQL script demonstrates how to create a table, insert data, and run several queries on the Managers table. The table is structured to allow for detailed tracking of manager information, including salary, department, and other personal details.

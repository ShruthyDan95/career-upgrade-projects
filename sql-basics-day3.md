1. Get all employee records

SELECT * FROM Employees;

2. Get all employees in the HR department

SELECT FirstName, LastName, Department FROM Employees
WHERE Department = 'HR';

3. Get top 5 highest-paid employees

SELECT FirstName, LastName, Salary FROM Employees
ORDER BY Salary DESC LIMIT 5;

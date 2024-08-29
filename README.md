SELECT unique_id, name 
<br>
FROM Employees
<br>
LEFT JOIN EmployeeUNI
<br>
ON Employees.id = EmployeeUNI.id;

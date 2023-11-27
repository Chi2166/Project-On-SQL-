# Project-On-SQL-

## These business questions were created to tackle some business problems.
1.	Find the sum of sales for all employees.
2.	Find the number of rows in the employee table.
3.	What is the highest amount increased yearly?
4.	Order Name and sales with row number from employee.
5.	What is the total sales made by each employee?
6.	What is the average yearly increment by employee ID?
7.	Show employees having yearly increments greater than 3000.
8.	Retrieve first name, City, yearly increment from employee and salary table.
9.	Retrieve first name, yearly increment, city and education from salary and department.
10.	Subquery name and sales.

-- From the below table, I ran a query on total sale from employee's table using the SELECT and SUM funtions.

![Project_Aggregate_Function_Sum](https://github.com/Chi2166/Project-On-SQL-/assets/144334275/be8aa08c-f20f-43a5-b701-7b09f70b87f2)

-- From the table below, I ran a query to find out the number of rows in the employee table using the SELECT COUNT from employee's table.

![Project_ on_Aggregate_function_Count](https://github.com/Chi2166/Project-On-SQL-/assets/144334275/73de2bd8-e88e-47c0-ac24-22090bf8427b)

-- From the table below, I ran a query to get the maximum yearly increment using the SELECT and MAX function. 

![Project_ on_Aggregate_function_Max](https://github.com/Chi2166/Project-On-SQL-/assets/144334275/864cabc4-d090-4a6c-a6ef-72f9a26d6dae)

-- From the table below, I ran a query on average yearly increment using the SELECT, AVG, AS and GROUP BY function from Salary table. 

![Poject_on_Group_by_fxn_on_Average_Yearly_Increment](https://github.com/Chi2166/Project-On-SQL-/assets/144334275/a94377ae-b6a4-4e5c-b1ec-2a961f21831f)

-- From the table below, I ran a query on total sale using the SELECT, SUM and GROUP BY function from employee's table.

![Project_on_Group_by_ON_TOTAL_SALES](https://github.com/Chi2166/Project-On-SQL-/assets/144334275/b082fe46-6acf-4dd0-81db-5c92be102f56)

-- From the table below, I ran a query on average yearly increment using the SELECT, AVG, AS, GROUP BY and HAVING YEARLY INCREMENT > 3000 function from Salary table. 

![Project_on_Having_Yearly_increment_GREATER_THAN_3000](https://github.com/Chi2166/Project-On-SQL-/assets/144334275/a90a0684-4407-4cef-9368-bbffd197a6d0)

-- From the table below, I ran a query using SELECT, ROW NUMBER(), OVER (ORDER BY DESC), AS NUMBER function from employee's table.

![Row_number](https://github.com/Chi2166/Project-On-SQL-/assets/144334275/57873c1b-7c6f-4cbf-9810-1de4e3f55509)

-- From the table below, I ran a query selecting first name, City, Yearly increment FROM employee JOIN salary, ON employee. Employee ID . Salary. Employee ID. 

![Project_on_Join_Employee_Salary_](https://github.com/Chi2166/Project-On-SQL-/assets/144334275/8c28f270-ffbc-47b3-b53f-096f6d17e666)

-- From the table below, I ran a query selecting first name, City, Yearly increment, City, Education, FROM employee LEFT JOIN salary, ON employee. Employee ID . Salary. Employee ID. RIGHT JOIN Department ON employee. department ID. Department . Department ID.

![Project_on_Left_Join_on_Right_ Join_](https://github.com/Chi2166/Project-On-SQL-/assets/144334275/1b338ff9-8b60-46ac-828e-b7db769e7f2b)

-- From the tabl below, I ran a query to subquery Name, City, Sales, and Phone where City = Mumbai, using the SELECT function, SELECT Name,SUM(sales) AS Sales GROUP BY Name from employee.s table.

![Project_on_Subquery](https://github.com/Chi2166/Project-On-SQL-/assets/144334275/aa84c85b-0afa-4db6-b471-ef2f74c1448a)

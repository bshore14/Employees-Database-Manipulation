SELECT 
    dept_no
FROM
    departments;

SELECT 
    *
FROM
    departments;
    
SELECT 
    *
FROM
    employees
WHERE
    first_name = 'Elvis';
    
SELECT 
	*
FROM 
	employees
WHERE
	first_name = 'Kellie' AND gender = 'F';
    
SELECT
	*
FROM
	employees
WHERE
	first_name = 'Denis' OR first_name = 'Elvis';

SELECT 
	*
FROM
	employees
WHERE 
	first_name = 'Kellie' OR first_name = 'Aruna';
    
SELECT 
	*
FROM
	employees
WHERE
	first_name = 'Denis' AND (gender = 'M' OR gender = 'F');
    
SELECT 
	*
FROM 
	employees
WHERE
	gender = 'F' AND (first_name = 'Kellie' OR first_name = 'Aruna');
    
SELECT
	*
FROM
	employees
WHERE
	first_name IN ('Cathie','Mark','Nathan');

SELECT
	*
FROM 
	employees
WHERE 
	first_name IN ('Denis','Elvis');
    
SELECT
	*
FROM 
	employees
WHERE
	first_name NOT IN ('John','Mark','Jacob');
    
SELECT 
    *
FROM
    employees
WHERE
	first_name LIKE ('Mark%');

SELECT 
    *
FROM
    employees
WHERE
	hire_date LIKE ('%2000%');
    

SELECT 
    *
FROM
    employees
WHERE
	emp_no LIKE ('1000_');
    
SELECT 
    *
FROM
    employees
WHERE
    first_name LIKE ('%jack%');

SELECT 
    *
FROM
    employees
WHERE
    first_name NOT LIKE ('%jack%');

SELECT 
    *
FROM
    salaries
WHERE
    salary BETWEEN 66000 AND 70000;
    
SELECT 
    *
FROM
    salaries
WHERE
    emp_no NOT BETWEEN ('10004') AND ('10012');   
    
SELECT 
    *
FROM
    departments
WHERE
    dept_no IS NOT NULL;
    
SELECT 
    *
FROM
    employees
WHERE
    hire_date >= '2000-01-01'
        AND gender = 'F';

SELECT 
    *
FROM
    salaries
WHERE
    salary > 150000; 
    
SELECT DISTINCT
    hire_date
FROM
    employees;

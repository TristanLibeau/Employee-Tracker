# Employee-Tracker

## Introduction

Employee-Tracker Application:

This application is a simple tool to track your employees. To install it simply git clone it on your pc, then in the terminal move to the app folder, then type:

* npm install
* npm start

If you still have issues starting the app run mysql -u root -p and source schema.sql and sedds.sql. Then run npm start again.

Don't forget to create a .env file.

## Links

* URL of my Repository:

https://github.com/TristanLibeau/Employee-Tracker

* Link to deomstration video:

https://drive.google.com/drive/folders/1H36uuNEIwHTfqtoMxunW6wnTgFf0QGxT?usp=sharing


## Functionality:

* WHEN I start the application
THEN I am presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role
* WHEN I choose to view all departments
THEN I am presented with a formatted table showing department names and department ids
* WHEN I choose to view all roles
THEN I am presented with the job title, role id, the department that role belongs to, and the salary for that role
* WHEN I choose to view all employees
THEN I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to
* WHEN I choose to add a department
THEN I am prompted to enter the name of the department and that department is added to the database
* WHEN I choose to add a role
THEN I am prompted to enter the name, salary, and department for the role and that role is added to the database
* WHEN I choose to add an employee
THEN I am prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database
* WHEN I choose to update an employee role
THEN I am prompted to select an employee to update and their new role and this information is updated in the database




## Mock-Up 

* The following Gif shows the process of the final application

![mock-up](./asset/img/employee-tracker.gif)

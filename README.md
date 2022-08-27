# SQL-Employee-Tracker
> This is a command line application that allows a user to manage information on employees within a company. The application connects to a database housed in MySQL that contains three tables with information on departments, roles, and employees within the company. This Content Management System allows a user to add, view, and modify information about employees of a company.
 
## Table of contents
* [User Story](#user-story)
* [General Info](#general-info)
* [Technologies](#technologies)
* [Video Example](#video-example)
* [Sources](#sources)
* [Contact](#contact)

## User Story
```md
AS A business owner
I WANT to be able to view and manage the departments, roles, and employees in my company
SO THAT I can organize and plan my business
```

## General Info
The database was initialized in MySQL Workbench after the schema files were set up (schema files included in repository). Data for employees was then seeded into the database after initialization. Upon running the program via the command line interface, a user can select to view all departments, view all roles, view all employees, add a department, add a role, add an employee, update an employee's current role, update an employee's current manager, remove an employee, remove a department, remove a role, and get the total salary for a specific department. After executing any of the add, update, or remove functions, the database is updated automatically.

## Technologies
* Javascript
* Node
* NPM Inquirer
* NPM MySQL
* NPM console.table
* MySQL
* MySQL Workbench

## Video Example
[MySQL Employee Management System](https://drive.google.com/file/d/1_20AT6cerIgXbkMycODh86IQtiO5k_qQ/view)

## Sources
Application enabled using the following sources:

* [NPM Inquirer](https://github.com/SBoudrias/Inquirer.js/)
* [NPM MySQL](https://www.npmjs.com/package/mysql)
* [NPM console.table](https://www.npmjs.com/package/console.table)

## Contact
Created by Huw Richmond
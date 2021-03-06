# Employee-tracker

<h1> Summary </h1>

This applications main purpose is too utilize eployee information and store it in a database. Employee tracker app is a CLI application for maintaining employee info for large companies. I used MysSQL and javascript to complete the functionality of this application. This app is scalable and allows managers or department heads to view all employees and allows the adddition of employees.

# employee-tracker



### Instructions:

In order to use this application you will need to first run an npm install in your CLI to install the dependencies that have been loaded into the json files for you. Once this is done, run node app.js in your CLI to start the prompts that will walk you through the verious tasks you can perform with this application.

## Technologies Used

- MySQL: Relational database management system based on SQL – Structured Query Language, used in this applicationt to warehouse and query employee and company data.
- Express.js - Used for application set up of middle ware for end point connection between the front end and backend.
- Node.js - Used for package managment and to execute JavaScript code to build command line tool for server-side scripting.
- Javascript - Used to base functionality of functions and prompts within the application.
- Git - Version control system to track changes to source code
- GitHub - Hosts repository that can be deployed to GitHub Pages

## Code Snippet

The following code snippet shows the schema that is the base for our link between our app.js file that oeprates the functions for building upon our employee regestry, and data base we create with this same schema setup in our sql workbench. Once these two are connected via calling upon our required mysql package and connection port and host thats configured in our JavaScript. We can then execute the functionality of the application through our JavaScript.

```sql
DROP DATABASE IF EXISTS employee_trackerDB;

CREATE DATABASE employee_trackerDB;

USE employee_trackerDB;

CREATE TABLE department
(
  id INT NOT NULL
  AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR
  (30)

);

```

## Built With

- [MySQL](https://www.mysql.com/)
- [Express.js](https://expressjs.com/)
- [Node.js](https://nodejs.org/en/)
- [npmjs](https://docs.npmjs.com/)
- [inquirer](https://www.npmjs.com/package/inquirer)

link to video of funtioning application
https://youtu.be/suOPc5MFGQg

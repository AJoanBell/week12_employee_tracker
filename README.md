# Week 12 Challenge - Employee Tracker

## The Task

Developers frequently have to create interfaces that allow non-developers to easily view and interact with information stored in databases. These interfaces are called **content management systems (CMS)**. Your assignment this week is to build a command-line application from scratch to manage a company's employee database, using Node.js, Inquirer, and MySQL.

Because this application won’t be deployed, you’ll also need to create a walkthrough video that demonstrates its functionality and all of the following acceptance criteria being met. You’ll need to submit a link to the video and add it to the README of your project.

## User Story

```md
AS A business owner
I WANT to be able to view and manage the departments, roles, and employees in my company
SO THAT I can organize and plan my business
```

## Acceptance Criteria

```md
GIVEN a command-line application that accepts user input
WHEN I start the application
THEN I am presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role
WHEN I choose to view all departments
THEN I am presented with a formatted table showing department names and department ids
WHEN I choose to view all roles
THEN I am presented with the job title, role id, the department that role belongs to, and the salary for that role
WHEN I choose to view all employees
THEN I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to
WHEN I choose to add a department
THEN I am prompted to enter the name of the department and that department is added to the database
WHEN I choose to add a role
THEN I am prompted to enter the name, salary, and department for the role and that role is added to the database
WHEN I choose to add an employee
THEN I am prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database
WHEN I choose to update an employee role
THEN I am prompted to select an employee to update and their new role and this information is updated in the database 
```
## Installation

To install necessary dependencies, run the following command:

npm i

## Usage
To use the application:

* Clone the repository to your desktop.
* Open the repository in your terminal or bash.
* Log into MySQL by entering mysql -u root -p in the command line, using ScreenQueen as the password.
* Create the database by entering SOURCE ./db/schema.sql;.
* (Optional) Seed the database with sample data by entering SOURCE ./db/seeds.sql;.
* Quit MySQL by entering quit.
* Start the application by entering node index.js.
* Use the application by answering the prompts.

## Bonus

Added some additional functionality to the application, such as the ability to do the following:

* Update employee managers.

* View employees by manager.

* View employees by department.

* Delete departments, roles, and employees.


## Screenshots 

Screenshot of some functionality in terminal:

<img width="2017" alt="functionality_screenshot" src="https://user-images.githubusercontent.com/36496885/206898233-d6f58243-72fb-4ae4-b2f7-49e662c16265.png">

Link to screenshot: https://github.com/AJoanBell/week12_employee_tracker/blob/main/assets/images/functionality_screenshot.png

### Technical Credit

    * Uses the [Inquirer package](https://www.npmjs.com/package/inquirer/v/8.2.4).

    * Uses the [MySQL2 package](https://www.npmjs.com/package/mysql2) to connect to a MySQL database.

    * Uses the [console.table package](https://www.npmjs.com/package/console.table) to print MySQL rows to the console.


## Review and Submission

Submit BOTH of the following for review:

* A walkthrough video demonstrating the functionality of the application: https://github.com/AJoanBell/week12_employee_tracker/blob/main/assets/video_walkthrough/employee_tracker_full_functionality.mp4

* Video walkthrough on google drive here: https://drive.google.com/file/d/1Ub1exsyzuyTaCrKYZFoSQnMd-h7Sk-Wi/view?usp=sharing

* The URL of the GitHub repository, with a unique name and a README describing the project: https://github.com/AJoanBell/week12_employee_tracker

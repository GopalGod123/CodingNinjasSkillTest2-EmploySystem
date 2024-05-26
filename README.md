

# Employee-Review-System
A full stack, app used for reviewing employee.


### Description

This application allows an admin to manage employee reviews. The admin can assign employees to review each other based on their work. Admins have special privileges, including promoting other employees to admin status, adding new employees, assigning reviewers and reviewees, and removing employees based on their reviews. All reviews are stored in the database.


### Tech Stack
Node.js
Express
MongoDB
EJS
JavaScript
HTML
CSS
Setup Instructions
Clone the repository to your local system.
Install npm if you don't have it already.
Navigate to the project directory and run the following commands

### How to setup the project on local system

  1. Clone this project
  2. Start by installing npm if you don't have it already.
  3. Navigate to Project Directory.

After reaching the project directory you have to run the following the command.
   ```` 
        npm install 
        npm start || nodemon index.js
   ````

#### If you want to make an employee as admin then use the secret key : happy.

### Features

  You can review the employees. The admin has the special power to assing, the task to employee, remove the employee, add new admin, and also employee;
    
  # HomePage / Admin View

  # Home page / Employee view
  
  # Sign-Up

  # Sign-In

  # Forget Password
  
  # Assign Task

  # Employee List
  

  

### Folder Structure

```
Employee Review System
    ├── assets
    │   ├── css
    │   └── images
    │
    ├── config
    │   ├── flashMiddleware.js
    │   ├── mongoose.js
    │   └── passport-local-Stradegy.js
    │
    ├── controllers
    │   ├── admin_controller.js
    │   ├── home_controller.js
    │   ├── review_controller.js
    │   └── user_controller.js
    │
    ├── models
    │   ├── review.js
    │   └── user.js
    │
    ├── routes
    │   ├── admin.js
    │   ├── index.js
    │   ├── review.js
    │   └── user.js
    │
    ├── views
    │   ├── _header.ejs
    │   ├── addEmployee.ejs
    │   ├── admin.ejs
    │   ├── employee.ejs
    │   ├── forget_password.ejs
    │   ├── home.ejs
    │   ├── layout.ejs
    │   ├── sign_in.ejs
    │   └── sign_up.ejs
    │
    ├── node_modules
    ├── .gitignore
    ├── index.js
    ├── package-lock.json
    └── package.json

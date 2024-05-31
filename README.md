Employee Review System by Gopal Khandelwal
Welcome to the Employee Review System, a full-stack application designed to streamline employee evaluation processes.

Description
Crafted by Gopal Khandelwal, the Employee Review System empowers administrators to assign employees for peer reviews based on their work performance. Administrators possess special privileges, including the ability to designate new administrators, create employee profiles, and assign roles such as reviewer and reviewee. The system also enables administrators to view current employees and take action, such as removing employees based on performance reviews. All reviews are securely stored in the database for future reference.

Tech Stack
This application leverages the following technologies:

Node.js
Express.js
MongoDB
EJS (Embedded JavaScript)
JavaScript
HTML
CSS
Setup Instructions
To set up the project locally, follow these steps:

Clone the project repository.
Ensure npm is installed on your system.
Navigate to the project directory in your terminal.
Run the following commands:
bash
Copy code
npm install
npm start
If you prefer using nodemon:

bash
Copy code
npm install -g nodemon   # Install nodemon globally if not already installed
nodemon index.js
To grant administrator privileges, use the secret key: happy.

Features
Key features of the Employee Review System include:

Ability to review employees
Administrator privileges to assign tasks, remove employees, designate new administrators, and add employees
User-friendly interface for seamless navigation and interaction
Screenshots
Home Page / Admin View
Home Page / Employee View
Sign-Up
Sign-In
Forget Password
Assign Task
Employee List
Folder Structure
sql
Copy code
Employee Review System
    |
    |---> assets
    |       |---> css
    |       |---> images
    |
    |---> config
    |       |---> flashMiddleware.js
    |       |---> mongoose.js
    |       |---> passport-local-Stradegy.js
    |
    |---> controllers
    |       |---> admin_controller.js
    |       |---> home_controller.js
    |       |---> review_controller.js
    |       |---> user_controller.js
    |
    |---> models
    |       |---> admin.js
    |       |---> review.js
    |       |---> user.js
    |
    |---> routes
    |       |---> index.js
    |       |---> review.js
    |       |---> user.js
    |
    |---> views
    |       |---> _header.ejs
    |       |---> addEmployee.ejs
    |       |---> admin.ejs
    |       |---> employee.ejs
    |       |---> forget_password.ejs
    |       |---> home.ejs
    |       |---> layout.ejs
    |       |---> sign_in.ejs
    |       |---> sign_up.ejs
    |
    |---> node_modules
    |
    |---> .gitignore
    |---> index.js
    |---> package-lock.json
    |---> package.json

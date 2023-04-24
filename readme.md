Registration and Login Application:

This is a simple registration and login application built using ExpressJS. The application utilizes Express Session and Express Validator for validation purposes, as well as bcryptjs for password hashing. User data is stored in a JSON file (users.json) and new users can be registered by filling out a registration form.

----------------------------------------
Prerequisites:
Before using the application, make sure you have Node.js and npm installed on your system.

-----------------------------------------
Installation:

To install the dependencies, run the following command in the project directory:

npm install

To start the application, run the following command:

nodemon app

-----------------------------------------
The application will be available at http://localhost:3000.

Registration
To register as a new user, navigate to http://localhost:3000/user/register and fill out the registration form. The form includes fields for username, email, and password. Once the form is submitted, the application will create a new user and store their information in the users.json file.

Login
To login, navigate to http://localhost:3000/user/login and enter your username and password. If the information is valid, you will be redirected to the home page. Otherwise, an error message will be displayed.

Validation
Both the registration and login forms are validated using Express Validator to ensure that the data is entered correctly.

Password Security
To ensure password security, bcryptjs is used to hash the passwords before they are stored in the users.json file. This means that even if the file is accessed by unauthorized users, they will not be able to read the passwords in plain text.

Contributor:
Gabriel Bocchio
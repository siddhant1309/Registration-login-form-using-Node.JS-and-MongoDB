# Node.js Registration & Login Form

This is a simple web application built with Node.js, Express.js, EJS, and MongoDB that provides registration and login functionality.

## Features

- **User Registration:** Allows users to create a new account by providing a username and password. Passwords are securely hashed before storing in the database.
- **User Login:** Allows registered users to log in using their username and password.
- **Session Management:** Uses session management to keep track of logged-in users.
- **Security:** Implements security measures to protect against common web vulnerabilities.
- **MongoDB Integration:** Stores user data securely in a MongoDB database.

## Prerequisites

Before running this application, ensure you have the following installed:

- Node.js
- MongoDB

## Installation

1. Clone the repository:

git clone https://github.com/siddhant1309/Registration-login-form-using-Node.JS-and-MongoDB.git


2. Install dependencies:

cd registration-login-form
npm install


3. Set up environment variables:

Create a `.env` file in the root directory and provide the following variables:

PORT=5000
MONGODB_URI=mongodb://localhost:27017/Login
SESSION_SECRET=your_session_secret_key


## Usage

1. Start the server:

npm start


2. Open your web browser and navigate to `http://localhost:5000` to access the application.

3. You can register a new account or log in with existing credentials.

## File Structure

- **index.ejs:** Entry point of the application, contains route handling for login and signup.
- **login.ejs:** HTML template for the login page.
- **signup.ejs:** HTML template for the signup page.
- **home.ejs:** HTML template for the home page.
- **config.js:** Contains database configuration and schema definition.
- **style.css:** CSS file for styling HTML templates.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).


## Contact

For any inquiries or feedback, please contact Siddhant Pathak at siddhantpathak13@gmail.com

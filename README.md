# Express Authentication Examples

This repository contains two basic Express.js projects demonstrating user authentication concepts: **user registration** and **user login**. These examples use **sessions** to manage user state and **EJS** for rendering views.

## Installation and Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Keyin-SD14-S3/user-authentication-examples.git
cd express-auth-examples
```

### 2. Install Dependencies
Each project has its own dependencies. Navigate into the desired project folder and install the dependencies.

For **Simple Registration**:
```bash
cd simple-registration
npm install
```

For **Simple Login**:
```bash
cd simple-login
npm install
```

### 3. Run the Server
Inside the respective project directory, run:
```bash
node server.js
```
The application will be accessible at `http://localhost:3000`.

## Project Structure

```
/express-auth-examples
│── /simple-registration  # Project for user registration
│── /simple-login         # Project for user login
│── README.md             # Project documentation
```

Each project has the following structure:

```
/project-folder
│── /views        # EJS templates
│── /public       # Static files (CSS, JS, images)
│── server.js     # Main Express server file
│── package.json  # Dependencies and scripts
```

## Projects

### **Simple Registration**
- Demonstrates how a user can **register** on a website.
- Uses an in-memory array to store users temporarily.
- Includes form handling and session management.
- Redirects to a homepage after registration.

### **Simple Login**
- Demonstrates how a user can **log in** using a username and password.
- Uses hardcoded user credentials for authentication.
- Stores login state in a session.
- Allows users to log out.

## Future Improvements

- Store users in a database instead of an in-memory array.
- Hash passwords before storing them.
- Improve error handling and display messages for failed actions.

## License

This project is for educational purposes only.
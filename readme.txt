# MongoLoginApp

## Overview

MongoLoginApp is a simple Node.js-based login application using Express and MongoDB. It demonstrates basic user authentication with registration and login functionality, storing user data securely in a MongoDB database.

## Features

- User registration with email and password
- Secure login functionality
- Password hashing using bcrypt
- MongoDB for data storage via Mongoose
- Basic form validation
- Express.js routing and middleware setup

## Requirements

- Node.js (v14 or higher recommended)
- MongoDB (local or remote)
- npm


**Set up environment variables:**

Create a `.env` file in the root directory with the following contents:

4. **Run the application:**


5. **Visit the app:**

Open your browser and go to:  
[http://localhost:3000](http://localhost:3000)

## File Structure

- `server.js` – Main entry point of the app
- `/routes` – Contains route definitions for login, register, etc.
- `/models` – Mongoose models for users
- `/views` – EJS templates (or whichever view engine you're using)
- `/public` – Static assets (CSS, JS, images)
- `.env` – Environment variables (not included for security)

## Notes

- Make sure MongoDB is running locally or update `MONGODB_URI` in `.env` for a remote connection.
- Passwords are securely hashed using bcrypt.
- Sessions are managed via express-session.

## License

This project is licensed under the MIT License.

## Author

Developed by [Your Name]  
Contact: [your.email@example.com]





# MERN Stack Authentication Project

This project is a full-stack web application built using the MERN (MongoDB, Express.js, React, Node.js) stack for user authentication. It allows users to register, log in, and log out.The frontend is built with React and styled using Bootstrap, while the backend is built with Node.js and Express.js, with MongoDB as the database.



## Features

- User registration with username, name, surname, email, phone, and password
- User login with email and password
- User authentication using JWT (JSON Web Tokens)
- User logout functionality
- Display of user details
- Responsive design using Bootstrap for styling

## Technologies Used

- MongoDB: NoSQL database for storing user information
- Express.js: Node.js framework for building the backend
- React: Frontend library for building the user interface
- Node.js: JavaScript runtime for running the backend server
- bcrypt.js: Library for hashing passwords
- jsonwebtoken: Library for generating and verifying JWT tokens
- Bootstrap: Frontend framework for responsive design

## Setup Instructions

1. Clone the repository: `git clone <repository-url>`
2. Install dependencies: `npm install`
3. Start the backend server: `cd back_end && node index or nodemon index`
4. Start the frontend development server: `cd front_end && npm start`

## API Endpoints

### Registration

- **URL:** `/api/auth/register`
- **Method:** `POST`
- **Request Body:** `{ "username": "abc", "name": "ABC", "surname": "DEF", "email": "abc@gmail.com", "phone": "1234567890", "password": "password" }`
- **Response:** `{ "msg": "User registered successfully" }`

### Login

- **URL:** `/api/auth/login`
- **Method:** `POST`
- **Request Body:** `{ "email": "abc@gmail.com", "password": "password" }`
- **Response:** `{ "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...", "user": { "id": "60710b73d8e87d09fc1865e8", "username": "abc", "name": "ABC", "surname": "DEF", "email": "abc@gmail.com", "phone": "1234567890" } }`

### Logout

- **URL:** `/api/auth/logout`
- **Method:** `GET`
- **Response:** `{ "msg": "Logged out successfully" }`

### Get All Users

- **URL:** `/api/users`
- **Method:** `GET`
- **Response:** Array of user objects

## Future Improvements

- Implement password reset functionality
- Add user profile update feature
- Enhance error handling and validation


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

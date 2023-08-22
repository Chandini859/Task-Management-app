# Task-Management-app
Screenshots:
![Screenshot (25)](https://github.com/Chandini859/Task-Management-app/assets/105451985/354ee72e-03a4-4786-b929-f6ca270a98db)
![Screenshot (26)](https://github.com/Chandini859/Task-Management-app/assets/105451985/2173adb5-064a-4edd-9fd5-912808568df3)
![Screenshot (27)](https://github.com/Chandini859/Task-Management-app/assets/105451985/a5d3b555-1d91-4d88-a760-d67943dd0db4)
![Screenshot (28)](https://github.com/Chandini859/Task-Management-app/assets/105451985/79bcdae2-6ea2-4785-8360-4b1fdda7a9e7)

Features:
User-side features:
Signup
Login
Logout
Add tasks
View tasks
Update tasks
Delete tasks

Developer-side features:
Toasts for success and error messages
Form validations in frontend and backend
Fully Responsive Navbar
Token based Authentication
Use of 404 page for wrong urls
Relevant redirects
Global user state using Redux
Custom Loaders
Use of layout component for pages
Use of theme colors
No external CSS files needed (made using Tailwind CSS)
Usage of Tooltips
Dynamic document titles
Redirect to previous page after login
Use of various React hooks
Custom hook also used (useFetch)
Routes protection
Middleware for verifying the user in backend
Use of different HTTP status codes for sending responses
Standard pratices followed

Tools and Technologies:
HTML
CSS
Javascript
Tailwind CSS
Node.js
Express.js
React
Redux
Mongodb

Dependencies:
axios
react
react-dom
react-redux
react-router-dom
react-toastify
redux
redux-thunk
bcrypt
cors
dotenv
express
jsonwebtoken
mongoose


Dev-dependencies:
nodemon
concurrently

Prerequisites:
Node.js must be installed on the system.
You should have a MongoDB database.
You should have a code editor (preferred: VS Code)

Installation and Setup:
1.Install all the dependencies

2.npm run install-all
Create a file named ".env" inside the backend folder. Add data from .env.example file and substitute your credentials there.

3.Start the application

4.npm run dev
Go to http://localhost:3000

Backend-API
- POST     /api/auth/signup
- POST     /api/auth/login
- GET      /api/tasks
- GET      /api/tasks/:taskId
- POST     /api/tasks
- PUT      /api/tasks/:taskId
- DELETE   /api/tasks/:taskId
- GET      /api/profile

Frontend Pages:
- /                 Home Screen 
- /signup           Signup page
- /login            Login page
- /tasks/add        Add new task
- /tasks/:taskId    Edit a task

npm scripts:
At root:

npm run dev: Starts both backend and frontend
npm run dev-server: Starts only backend
npm run dev-client: Starts only frontend
npm run install-all: Installs all dependencies and dev-dependencies required at root, at frontend and at backend.
Inside frontend folder:

npm start: Starts frontend in development mode
npm run build: Builds the frontend for production to the build folder
npm test: Launches the test runner in the interactive watch mode
npm run eject: This will remove the single build dependency from the frontend.
Inside backend folder:

npm run dev: Starts backend using nodemon.
npm start: Starts backend without nodemon.


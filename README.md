Project Title: MERN Stack Admin Panel
Project Overview
This project is a basic admin panel built using the MERN (MongoDB, Express.js, React.js, Node.js) stack.
It includes functionalities for user registration, login, logout, and CRUD operations on users.
The project demonstrates proficiency in both frontend and backend development using the MERN stack.

Project Setup
Prerequisites
Node.js
MongoDB
Frontend Setup
Initialize React Project:

npx create-react-app admin-panel
cd admin-panel
Install Dependencies:
npm install axios react-router-dom redux react-redux bootstrap material-ui tailwindcss
Project Structure:

src/components: Reusable components
src/pages: Different pages
src/services: API calls
src/store: State management

Start Development Server:
npm start
Backend Setup
Initialize Node.js Project:


mkdir backend
cd backend
npm init -y
Install Dependencies:
npm install express mongoose bcrypt jsonwebtoken cors dotenv
Project Structure:

controllers: Handling requests
models: Database schemas
routes: API routes
middlewares: Custom middleware
config: Configuration files
Setup Environment Variables:

Create a .env file in the backend directory and add the following:
makefile
Copy code
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
Start Server:
npm start
Running the Project
Frontend:

Navigate to the frontend directory:
cd admin-panel
Start the React development server:
npm start

Backend:

Navigate to the backend directory:
cd backend
Start the Node.js server:
npm start
Access the application at http://localhost:3000.


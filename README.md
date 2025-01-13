Task Manager Application

This is a simple task management application built with the MERN stack (MongoDB, Express, React, Node.js). The app allows users to create, manage, and complete tasks.

Features

Add new tasks with a title and description.

Mark tasks as completed or incomplete.

Delete tasks.

View a list of all tasks.

Technologies Used

Frontend: React.js, Axios

Backend: Node.js, Express.js, Mongoose

Database: MongoDB

Getting Started

Prerequisites

Node.js installed on your machine.

MongoDB Atlas account or a locally running MongoDB instance.

Installation

Clone the repository:

git clone https://github.com/your-repository/task-manager.git
cd task-manager

Install dependencies for both the frontend and backend:

cd task-backend
npm install

cd ../task-frontend
npm install

Set up a .env file in the task-backend directory:

PORT=5000
MONGO_URI=your_mongodb_connection_string_here

Run the backend server:

cd task-backend
npm run dev

Run the frontend:

cd ../task-frontend
npm start

Usage

Open your browser and navigate to http://localhost:3000 to access the task manager.

Use the form to add tasks with a title and description.

Click buttons to complete or delete tasks.

Folder Structure

project-root/
  ├── task-backend/
  │   ├── routes/
  │   ├── models/
  │   ├── index.js
  │   └── .env
  └── task-frontend/
      ├── src/
      │   ├── components/
      │   │   ├── TaskList.js
      │   │   ├── TaskForm.js
      │   │   └── TaskItem.js
      │   ├── App.js
      │   └── App.css
      └── public/

Future Enhancements

Add user authentication.

Categorize tasks with tags or labels.

Allow task editing.

License

This project is licensed under the MIT License.


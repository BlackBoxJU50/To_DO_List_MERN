# To-Do List Application (MERN Stack)

A modern, full-stack To-Do List application built using the MERN (MongoDB, Express, React, Node.js) stack. This application allows users to register, log in, and manage their tasks with real-time updates and a responsive UI.

## Overview
This project provides a robust task management system where users can keep track of their daily activities. Each user has their own isolated task list, ensuring privacy and organization. The frontend is built for speed and responsiveness, while the backend ensures secure data handling and persistent storage.

## Features

### Frontend
- **Responsive UI**: Built with Bootstrap for a clean and mobile-friendly experience.
- **User Authentication**: dedicated pages for User Registration and Login.
- **Dynamic Dashboard**: Interactive task management interface.

### Backend
- **RESTful API**: Developed using Express.js to handle user data and task operations.
- **Secure Authentication**: Backend logic to verify user credentials.
- **Task Management**: Endpoints for full CRUD (Create, Read, Update, Delete) functionality.

### Database
- **Persistent Storage**: MongoDB is used to store user profiles and tasks.
- **Relational Integrity**: Tasks are linked to specific users via email identifiers.

### Task Management
- **Create**: Quickly add new tasks to your list.
- **Read**: View your personalized task list upon logging in.
- **Update**: Mark tasks as completed or edit task descriptions.
- **Delete**: Remove tasks from your list with a single click.

## Tech Stack
- **Frontend**: React.js, Vite, Bootstrap, Axios, React Icons, React Router
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose ODM)
- **Tooling**: Nodemon (for development)

## Setup Instructions

### Prerequisites
- Node.js installed on your machine.
- MongoDB database (local or Atlas).

### 1. Clone the repository
```bash
git clone https://github.com/BlackBoxJU50/To_DO_List_MERN.git
cd To_DO_List_MERN
```

### 2. Backend Setup
```bash
cd server
npm install
npm start
```
*The server will run on [http://localhost:3000](http://localhost:3000)*

### 3. Frontend Setup
```bash
cd ../client
npm install
npm run dev
```
*The frontend will run on [http://localhost:5173](http://localhost:5173)*

## Links
- **Live Demo(Deployed on render, Please wait for a while it might take some time to build)**: [[Link to your live site]](https://my-todo-list-qej5.onrender.com/)
- **Video Presentation**: [[Link to your video presentation]](https://drive.google.com/file/d/167XkIlqAvwFSMKBP49xF_MoLdjUN-riu/view?usp=sharing)

---
Developed by **Md Hasib Ahmed Khan**

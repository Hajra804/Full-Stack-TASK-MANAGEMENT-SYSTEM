# Full-Stack-TASK-MANAGEMENT-SYSTEM
HTML,CSS,JAVA,.JS, MongoDB
# Task Management System

## Overview

The **Task Management System** is a full-stack web application designed to help users organize, manage, and track their daily tasks efficiently. It provides a simple and intuitive interface for creating tasks, setting priorities, monitoring progress, and managing deadlines.

The application includes secure user authentication, protected routes, task analytics, and an administrator panel for managing users and monitoring overall system activity.

---

## Features

### User Features

* User registration and authentication
* Secure login and logout
* Create new tasks
* Edit existing tasks
* Delete tasks
* View all personal tasks
* Search tasks by title
* Sort tasks by priority, deadline, or newest
* Update task status

  * Pending
  * In Progress
  * Completed
* Dashboard with task statistics
* Persistent user session

### Admin Features

* Manage registered users
* View overall system activity
* Access protected administrative routes
* Monitor application usage

---

## Technology Stack

### Frontend

* React
* Redux
* React Router
* Bootstrap
* Axios

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JSON Web Token (JWT)
* bcrypt

---

## Project Structure

```text
task-management-system/
│
├── client/              # React frontend
│
├── server/              # Express backend
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── config/
│
├── package.json
└── README.md
```

---

## Core Functionality

### Authentication

* User Sign Up
* User Sign In
* JWT-based Authentication
* Protected Routes
* User Profile Management

### Task Management

* Create Tasks
* View Tasks
* Update Tasks
* Delete Tasks
* Search Tasks
* Sort Tasks
* Track Progress
* Manage Priorities
* Set Due Dates

### Dashboard

* Total Tasks
* Pending Tasks
* Completed Tasks
* Task Progress Overview

---

## Application Workflow

1. Users create an account or sign in.
2. The dashboard displays all personal tasks.
3. Users create tasks with descriptions, priorities, and due dates.
4. Tasks can be updated as work progresses.
5. Completed tasks are reflected in dashboard statistics.
6. Users can edit or delete tasks at any time.
7. Administrators can manage users and monitor system activity.

---

## Installation

### Clone the Repository

```bash
git clone <repository-url>
```

### Install Dependencies

#### Backend

```bash
cd server
npm install
```

#### Frontend

```bash
cd client
npm install
```

---

## Running the Application

### Start Backend

```bash
npm run server
```

or

```bash
npm start
```

### Start Frontend

```bash
npm start
```

The frontend and backend should now be running locally.

---

## Future Enhancements

* Email notifications
* Task reminders
* Team collaboration
* File attachments
* Calendar integration
* Dark mode
* Real-time updates
* Task labels and categories
* Activity logs

---

## Learning Outcomes

This project demonstrates practical implementation of:

* Full-stack web development
* RESTful API development
* User authentication and authorization
* CRUD operations
* State management with Redux
* MongoDB database integration
* Protected routing
* Dashboard analytics
* Responsive UI development

## License

This project is intended for educational and portfolio purposes.

# Task Manager Project

A simple Task Manager application with a Node.js backend and a basic frontend interface.

## Project Structure

```
task-manager-project/
│
├── package.json
│
├── backend/
│   ├── server.js
│   ├── models/
│   │   ├── User.js
│   │   └── Task.js
│   ├── routes/
│   │   ├── authRoutes.js
│   │   └── taskRoutes.js
│   └── middleware/
│       └── auth.js
│
└── frontend/
    ├── index.html
    ├── style.css
    └── script.js
```

## Features

- User Authentication
- Task Management
- Frontend User Interface
- Backend API Structure
- Authentication Middleware

## Technologies Used

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Node.js
- Express.js (recommended)

## Installation

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate to the project directory:

```bash
cd task-manager-project
```

3. Install dependencies:

```bash
npm install
```

## Running the Project

Start the server:

```bash
node backend/server.js
```

Expected output:

```bash
Server running
```

## Backend Components

### Models
- **User.js** – User data model
- **Task.js** – Task data model

### Routes
- **authRoutes.js** – Authentication routes
- **taskRoutes.js** – Task-related routes

### Middleware
- **auth.js** – Authentication middleware

## Frontend Components

- **index.html** – Main webpage
- **style.css** – Styling
- **script.js** – Client-side JavaScript

## Future Enhancements

- User Registration and Login
- JWT Authentication
- CRUD Operations for Tasks
- Database Integration (MongoDB)
- Responsive UI
- Task Filtering and Search

## Author

Developed as a Task Manager application using Node.js and JavaScript.

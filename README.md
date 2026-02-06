# MERN Todo App

A full-stack **Todo Application** built using the **MERN** stack (MongoDB, Express.js, React.js, Node.js). This application allows users to add, update, delete, and view tasks in real-time, featuring a responsive UI and a persistent database connection.

## 🚀 Live Demo
*(Optional: Add your deployed link here, e.g., on Vercel or Render)*
> [View Live Demo](https://your-deployment-link.com)

## ✨ Features
- **Create Tasks:** Add new todos to the list.
- **Read Tasks:** View all current todos fetched from the database.
- **Update Tasks:** Edit existing tasks or mark them as completed.
- **Delete Tasks:** Remove tasks permanently.
- **Responsive Design:** Works seamlessly on desktop and mobile.
- **RESTful API:** Backend built with Express & Node.js.
- **Database:** MongoDB for persistent data storage.

## 🛠️ Tech Stack

### Frontend
- **React.js** (Functional Components & Hooks)
- **Axios** (API requests)
- **CSS / Tailwind** (Styling)

### Backend
- **Node.js** (Runtime environment)
- **Express.js** (Web framework)
- **MongoDB** (NoSQL Database)
- **Mongoose** (ODM for MongoDB)
- **Cors** (Cross-Origin Resource Sharing)

## 📂 Project Structure
```bash
mern-todo_app/
├── client/         # React Frontend
│   ├── src/
│   ├── public/
│   └── package.json
├── server/         # Node/Express Backend
│   ├── models/     # Mongoose Models
│   ├── routes/     # API Routes
│   ├── index.js    # Server Entry Point
│   └── package.json
└── README.md
⚙️ Installation & SetupFollow these steps to run the project locally.1. Clone the repositoryBashgit clone [https://github.com/ash161204/mern-todo_app.git](https://github.com/ash161204/mern-todo_app.git)
cd mern-todo_app
2. Backend SetupNavigate to the server directory and install dependencies.Bashcd server
npm install
Environment Variables:Create a .env file in the server/ folder and add your MongoDB connection string:Code snippetMONGO_URI=your_mongodb_connection_string
PORT=5000
Start the server:Bash npm start
# Server should run on http://localhost:5000
3. Frontend SetupOpen a new terminal, navigate to the client directory, and install dependencies.Bashcd ../client
npm install
Start the React app:Bashnpm start
# Client should run on http://localhost:3000
🔌 API EndpointsMethodEndpoint
Description   GET/api/todos                      Get all tasks
              POST/api/todos/new                 Create a new task
              PUT/api/todos/update/:id           Update a task status/content
              DELETE/api/todos/delete/:id        Delete a specific task

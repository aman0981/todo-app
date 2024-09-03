# todo-app
A full-stack ToDo app built with the MERN stack (MongoDB, Express.js, React.js, Node.js). It demonstrates RESTful APIs for CRUD operations and data persistence in MongoDB, highlighting best practices in backend development with Express.js, frontend UI/UX design with React.js, and seamless front-end and back-end integration

ToDo App
A full-stack ToDo application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). This project demonstrates the use of RESTful APIs for CRUD operations and showcases best practices in both backend and frontend development.

Features
Create, Read, Update, Delete (CRUD): Manage to-do items with full CRUD functionality.
RESTful API: Uses Express.js to create a RESTful API.
MongoDB Integration: Stores data persistently in MongoDB.
React Frontend: Interactive UI built with React.js.
Express Backend: Backend built with Express.js, handling routes and middleware.
Responsive Design: Mobile-first approach with a responsive design.
Tech Stack
Frontend:
React.js
HTML5
CSS3
JavaScript (ES6+)
Backend:
Node.js
Express.js
Database:
MongoDB
Mongoose
Version Control:
Git
GitHub
Setup and Installation
Prerequisites
Make sure you have the following installed:

Node.js
npm (Node Package Manager)
MongoDB (Local or Atlas)
Installation Steps
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/todo-app.git
cd todo-app
Install server-side dependencies:

bash
Copy code
cd backend
npm install
Install client-side dependencies:

bash
Copy code
cd ../frontend
npm install
Set up environment variables:

Create a .env file in the backend directory and add your MongoDB URI:

plaintext
Copy code
PORT=5000
MONGO_URI=your_mongodb_connection_string
Run the application:

Backend:

bash
Copy code
cd backend
npm run dev
Frontend:

bash
Copy code
cd ../frontend
npm start
Access the app:

The frontend will be running on http://localhost:3000, and the backend API will be available at http://localhost:5000.

API Endpoints
GET /api/get: Fetch all to-do items.
POST /api/save: Add a new to-do item.
PUT /api/update/:id: Update an existing to-do item by ID.
DELETE /api/delete/:id: Delete a to-do item by ID.

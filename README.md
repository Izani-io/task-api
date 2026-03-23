Task Management API

A RESTful API built with Node.js, Express, and MongoDB for managing user tasks with categories, deadlines, and completion tracking.



Features

* User Authentication (Register & Login)
* JWT-based Authorization
* Create, Read, Update, Delete tasks
* Task categorization
* Deadline management
* Mark tasks as complete or incomplete
* User-specific task management



Tech Stack

* Node.js
* Express.js
* MongoDB (Mongoose)
* JWT (Authentication)
* bcryptjs (Password hashing)



Installation

1. Clone the repository:
   git clone https://github.com/YOUR_USERNAME/task-api.git

2. Navigate into the project:
   cd task-api

3. Install dependencies:
   npm install

4. Create a .env file and add:
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key

5. Run the server:
   npm run dev

---

API Endpoints

Auth

* POST /api/auth/register
* POST /api/auth/login

Tasks

* POST /api/tasks
* GET /api/tasks
* GET /api/tasks/:id
* PUT /api/tasks/:id
* DELETE /api/tasks/:id


Live URL


Author

Built by Israel Izani




 Author

Built by Israel Izani

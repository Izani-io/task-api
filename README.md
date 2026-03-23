 Blog API

A RESTful API built with Node.js, Express, and MongoDB for managing blog posts and comments.



 Features

* User Authentication (Register & Login)
* JWT-based Authorization
* Create, Read, Update, Delete blog posts
* Comment system on posts
* Role-based access control (User/Admin)



 Stack

* Node.js
* Express.js
* MongoDB (Mongoose)
* JWT (Authentication)
* bcryptjs (Password hashing)



 Installation

1. Clone the repository:
   git clone https://github.com/Izani-io/blog-api.git

2. Navigate into the project:
   cd blog-api

3. Install dependencies:
   npm install

4. Create a .env file and add:
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key

5. Run the server:
   npm run dev



 API Endpoints

 Auth

* POST /api/auth/register
* POST /api/auth/login

 Posts

* GET /api/posts
* GET /api/posts/:id
* POST /api/posts
* PUT /api/posts/:id
* DELETE /api/posts/:id

Comments

* POST /api/comments/:postId
* GET /api/comments/:postId
* DELETE /api/comments/:commentId

---

 Live URL



 Author

Built by Israel Izani

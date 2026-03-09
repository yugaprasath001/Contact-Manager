# 📇 Contact Manager API

A RESTful Contact Management System built using **Node.js, Express, and
MongoDB**. This project allows users to **register, authenticate, and
manage their contacts** securely through API endpoints.

This project was developed as part of the **Naan Mudhalvan program** to
demonstrate backend development using modern web technologies.

------------------------------------------------------------------------

# 🚀 Features

-   👤 User Registration
-   🔐 User Login with JWT Authentication
-   📇 Create Contacts
-   📄 View All Contacts
-   🔍 View Single Contact
-   ✏️ Update Contact
-   ❌ Delete Contact
-   🛡️ Protected Routes using Authentication Middleware
-   ✅ Input Validation
-   ⚠️ Error Handling Middleware

------------------------------------------------------------------------

# 🛠️ Technologies Used

-   Node.js
-   Express.js
-   MongoDB
-   Mongoose
-   JWT (JSON Web Token)
-   bcryptjs
-   Express Validator
-   Cors
-   Dotenv

------------------------------------------------------------------------

# 📂 Project Structure

    project-folder
    │
    ├── controllers
    ├── dbConfig
    ├── middleware
    ├── models
    ├── routes
    ├── utility
    │
    ├── index.js
    ├── package.json
    └── README.md

------------------------------------------------------------------------

# ⚙️ Installation

1.  Clone the repository

```{=html}
<!-- -->
```
    git clone https://github.com/yourusername/contact-manager-api.git

2.  Navigate to the project folder

```{=html}
<!-- -->
```
    cd contact-manager-api

3.  Install dependencies

```{=html}
<!-- -->
```
    npm install

------------------------------------------------------------------------

# ▶️ Running the Project

Start the server using:

    npm start

The server will start and connect to **MongoDB**.

Example:

    Server running on port 5000
    MongoDB Connected

------------------------------------------------------------------------

# 🔐 API Endpoints

## Authentication

  Method   Endpoint             Description
  -------- -------------------- -------------------
  POST     /api/auth/register   Register new user
  POST     /api/auth/login      Login user

## Contacts

  Method   Endpoint            Description
  -------- ------------------- --------------------
  GET      /api/contacts       Get all contacts
  GET      /api/contacts/:id   Get single contact
  POST     /api/contacts       Create new contact
  PUT      /api/contacts/:id   Update contact
  DELETE   /api/contacts/:id   Delete contact

------------------------------------------------------------------------

# 🧪 Testing the API

You can test the API using:

-   Thunder Client (VS Code)
-   Postman
-   Insomnia

Example request:

POST /api/auth/register

Body:

{ "name": "John", "email": "john@example.com", "password": "123456" }

------------------------------------------------------------------------

# 📚 Learning Objectives

This project demonstrates:

-   Backend API development
-   RESTful architecture
-   Authentication using JWT
-   MongoDB database integration
-   Middleware implementation
-   Error handling in Node.js

------------------------------------------------------------------------

# 👨‍💻 Author

**Yuga Prasath**

Project created for the **Naan Mudhalvan Skill Development Program**.

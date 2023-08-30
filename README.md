# JWT Authentication using MERN Stack

  ![MERN Logo](https://fiverr-res.cloudinary.com/images/t_main1,q_auto,f_auto,q_auto,f_auto/gigs/134630508/original/a34d495c81c1a61aef64879a4dfecfd788aa5856/mern-stack-application-development.jpeg)

This repository houses the backend implementation of a JWT (JSON Web Token) authentication system using the MERN (MongoDB, Express.js, React.js, Node.js) stack. The focus here is on the server-side functionality that provides secure user registration, login, and token-based authentication to protect certain API endpoints.

## Features

- User Registration API endpoint
- User Login API endpoint
- JWT Token generation upon login
- Middleware for token-based authentication for protected routes
- Logout and token invalidation logic
- User profile endpoint that's protected

## Prerequisites

1. Node.js
2. MongoDB
3. NPM or Yarn (preferred)

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/BabaYaGa74/MERN_JWT_Authentication.git
cd MERN_JWT_Authentication
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory and configure your environment variables:

```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000
```

### 4. Start the Development Server

From the root directory:

```bash
npm start
npm run server //nodemon
```

This will start the server on port 5000 by default.

## API Endpoints

- **POST** `/api/users/`: Register a new user.
- **POST** `/api/users/auth`: Login and receive a JWT token.
- **POST** `/api/users/logout`: Logout and remove a JWT token.
- **GET** `/api/users/profile`: Retrieve user profile (protected)
- **PUT** `/api/users/profile`: Update user profile (protected).
- 

## Tech Stack

- **Backend**: Node.js with Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Token


---

Developed by [Beeplove](https://github.com/BabaYaGa74)

---

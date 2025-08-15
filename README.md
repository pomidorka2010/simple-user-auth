# Simple User Auth

## Overview
This project is a simple RESTful API that allows users to register, log in, and manage their sessions using JSON Web Tokens (JWT) for authentication and authorization.

## Features
- User Registration
- Secure Login
- Token-based Authentication
- Role-based Access Control
- Refresh Token Mechanism

## Tech Stack
- Node.js
- Express.js
- MongoDB
- Mongoose
- bcrypt for password hashing

## Getting Started
### Prerequisites
- Node.js
- MongoDB

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/simple-user-auth.git
   ```
2. Navigate into the directory:
   ```bash
   cd simple-user-auth
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start MongoDB server (if you're using a local instance).
4. Configure environment variables for JWT secret and MongoDB URI in a `.env` file.

### Running the Application
```bash
npm start
```

### API Endpoints
- `POST /api/register`: Register a new user.
- `POST /api/login`: Authenticate a user and receive a token.
- `GET /api/protected`: Access a protected route.

## Contributing
Feel free to fork the repository and submit pull requests for any improvements or features you want to add!

## License
This project is licensed under the MIT License.

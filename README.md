# Backend User Authentication Application

Welcome !, This Node.js application provides a robust backend solution for user authentication, built with Express and MongoDB. Whether you're developing a web application, this backend offers secure user authentication features to ensure your users' data remains protected.

## Features

- **User Registration**: Allow users to sign up for an account with a unique username and password.
- **User Login**: Enable users to securely log in to their accounts using their credentials.
- **Password Encryption**: Implement secure password encryption to protect user data.
- **Rate Limiting**: Reduces the number of times a particular user can attempt to log in.

## Prerequisites

Before running the application, ensure you have the following prerequisites installed:

- [Node.js](https://nodejs.org) and npm (Node Package Manager)
- [MongoDB](https://www.mongodb.com) atlas account

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/backend-authentication.git
   ```

2. Navigate to the project directory:

   ```bash
   cd backend-authentication
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Create a .env file in the root directory and add the following variables:

   ```bash
      MONGODB_URI=your-mongodb-uri
   ```

5. Start the server:

```bash
   npm start
```

## Usage

Once the server is running, you can interact with the API using HTTP requests. Here are some example endpoints:

- **POST http://localhost:9090/user/signup:** Register a new user account.
- **POST http://localhost:9090/user/signin:** Log in to an existing user account.


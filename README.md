# Walmart Clone - Backend

This repository contains the backend code for the Walmart Clone project, a multi-vendor e-commerce platform. It is built using Node.js, Express.js, MongoDB, bcrypt, JSON Web Token (JWT), REST API, and integrates with Cloudinary for image hosting.

## Repository Structure

The repository is organized as follows:

- `/controllers`: Contains the controllers responsible for handling different routes and business logic.
- `/models`: Defines the data models and schemas for MongoDB.
- `/middlewares`: Contains middleware functions for authentication, error handling, etc.
- `/routes`: Defines the API routes and their corresponding handlers.
- `/utils`: Includes utility functions used throughout the project.
- `app.js`: The entry point of the backend server.
<!-- - `/config`: Contains configuration files for environment variables, database connection, etc. -->

## Deployment
This project deployed on this link: 'https://walmart-api.onrender.com'

## Getting Started

To get started with the backend development of the Walmart Clone project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/walmart-clone-backend.git

2. Install the dependencies:
   
   ```bash
    cd walmart-clone-backend
    npm install

3. Set up the environment variables:

  * Create a '.env' file in the root directory.
  * Define the required environment variables such as database connection details, Cloudinary credentials, JWT secret, etc.

4. Start the server:
   ```bash
    npm start
    
  The server should now be running on 'http://localhost:5000'. You can modify the port in the 'app.js' file if needed.
   
<!--## API Documentation
For detailed information about the API routes and their usage, please refer to the API documentation. You can find the documentation in the API Documentation file. -->

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

 1. Fork the repository.
 2. Create a new branch.
 3. Make your changes and commit them.
 4. Push your changes to your forked repository.
 5. Submit a pull request.
Please make sure to adhere to the code style and follow the existing conventions.

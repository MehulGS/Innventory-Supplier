A powerful backend API for managing Innventory App System, featuring robust CRUD operations and bulk processing capabilities.

Table of Contents

Features
Technologies Used
Installation
Usage
API Endpoints


Features
Create, read, update, and delete projects
Bulk upload and download of supply using CSV files
User-specific Stock retrieval



Technologies Used
Node.js: JavaScript runtime for building scalable applications
Express: Fast and minimalist web framework for Node.js
MongoDB: NoSQL database for storing project data
Mongoose: ODM for MongoDB, providing a schema-based solution
Multer: Middleware for handling multipart/form-data, used for file uploads (csv)
JSON Web Token (JWT): For secure authentication
Bcrypt: For hashing passwords


Installation
To get started with the Freelance App System, follow these steps:



cd library-system
Install the dependencies:


npm install

Create a .env file in the root directory and set up your environment variables.

Start the application:

npm run dev



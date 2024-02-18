# Project Title: Photo Sharing Platform
## Overview:

This project is a photo sharing platform built using Node.js, Express.js, MongoDB, and other related technologies. It allows users to upload, view, and interact with photos posted by other users. Key features include user authentication, email verification, photo uploading, liking photos, and browsing photos by pagination.

## Features:

- User Authentication: Users can sign up and sign in to the platform using their email and password. Passwords are securely hashed using bcrypt for storage.
- Email Verification: Upon signing up, users receive a verification email to confirm their email address. This adds an extra layer of security and ensures valid user accounts.
- Photo Upload: Authenticated users can upload photos to the platform. Photos are stored on the server, and their metadata (such as uploader, upload time) is stored in the database.
- Photo Interactions: Users can interact with photos by liking them. Each user can only like a photo once. The number of likes and dislikes for each photo is tracked and displayed.
- Pagination: The platform implements pagination for browsing photos. Users can navigate through pages of photos to discover new content.

## Technologies Used:

- Node.js: The backend runtime environment for running JavaScript server-side code.
- Express.js: A web application framework for Node.js used for routing and middleware.
- MongoDB: A NoSQL database used to store photo metadata and user information.
- Mongoose: An Object Data Modeling (ODM) library for MongoDB and Node.js, used to define schemas and interact with the database.
- Multer: A middleware for handling file uploads, used for uploading photos.
- JWT (JSON Web Tokens): Used for user authentication and authorization by generating and verifying tokens.
- Bcrypt: A library used for hashing passwords securely before storing them in the database.
- Nodemailer: Used for sending verification emails to users upon signup.

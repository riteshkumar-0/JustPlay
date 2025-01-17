# Project Name: JustPlay

## Overview

This project is a backend system designed to mimic functionalities similar to YouTube. It handles various aspects including user authentication, video streaming, comments, likes, playlists, and more.

### **Features**
- <u>**Authentication System**</u>: Implemented using JWT for secure access and maintaining user sessions.
- <u>**User Profiles**</u>: Manage user data and profiles including the creation, updates, and retrieval of user information.
- <u>**Video Management**</u>: Allow users to upload, update, delete, and retrieve videos. Integrated with Cloudinary for efficient media management.
- <u>**Comments and Likes**</u>: Users can comment on videos and like videos. Includes endpoints to manage these functionalities.
- <u>**Error Handling**</u>: Robust error handling to provide clear feedback for API users.
- <u>**Database Integration**</u>: Utilizes MongoDB for storing and managing data efficiently.
- <u>**Middleware**</u>: Custom middleware for handling authentication, logging, and other tasks.
- <u>**Cloudinary Integration**</u>: For handling uploads and storage of media files.
- <u>**API Routes**</u>: Well-defined API routes for handling various functionalities related to videos, users, and interactions.


### **Technologies Used**
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT for Authentication
- Cloudinary for Media Storage
- Various NPM packages (express-validator, bcryptjs, dotenv, etc.)

### **Prerequisites**
- Node.js installed on your machine
- MongoDB account and database set up
- Cloudinary account for handling media files

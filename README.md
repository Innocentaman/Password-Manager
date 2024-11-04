# **Password Manager Application**

A secure and efficient password management application built using the **MERN stack** (MongoDB, Express.js, React, Node.js). This application allows users to securely store their credentials (URLs, usernames, and passwords) and manage them with ease. Authentication and data encryption enhance the security, ensuring safe password storage.

---

## **Tech Stack**

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication & Security**: JWT (JSON Web Tokens), bcrypt.js

---

## **Functionality**

1. **User Registration & Authentication**
   - Users can register for an account with a secure password.
   - Authentication is handled using **JWT** tokens to ensure secure access.
   - Passwords are hashed using **bcrypt.js** for enhanced security.

2. **Password Management**
   - Users can securely save their credentials (URL, username, and password) for various websites and services.
   - Each password is encrypted before being stored in the database, ensuring it remains secure.
   - Users can view, edit, and delete their saved credentials.

3. **Responsive UI**
   - The application’s frontend is built with **React** and styled using **Tailwind CSS** for a clean and responsive user experience.

4. **CRUD Operations**
   - Full **CRUD (Create, Read, Update, Delete)** functionality for managing saved credentials.

---

## **How It Works**

- **Authentication Flow**:
  - User registers or logs in.
  - A JWT token is generated and stored in the client, which is then used for accessing secure routes.

- **Password Encryption**:
  - Passwords are hashed with **bcrypt.js** before storage, making them unreadable by unauthorized access.
  - Sensitive data is stored securely in MongoDB with encrypted fields.

- **Data Flow**:
  - Frontend communicates with the backend via **RESTful API** requests.
  - The backend interacts with MongoDB to store, retrieve, and manage data securely.

---

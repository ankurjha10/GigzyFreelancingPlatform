# Gigzy Fullstack Project

## Overview

Gigzy Fullstack is a freelancing platform designed with a modern full-stack architecture. It seamlessly integrates backend and frontend technologies to connect freelancers with clients for project-based work. This project highlights proficiency in API development, database management, and responsive user interfaces.

## Features

- User authentication and role-based authorization (freelancers and clients).
- Project posting and bidding system.
- Secure payment integration.
- Dynamic user dashboards for managing projects and bids.
- RESTful API endpoints for seamless communication between frontend and backend.
- Modular and scalable code structure.
- Responsive design optimized for all devices.

## Tech Stack

### Backend

- **Node.js**: Runtime environment.
- **Express.js**: Web framework for creating API endpoints.
- **MongoDB**: Database for storing user and project data.
- **Mongoose**: ODM for MongoDB.
- **JWT**: Secure user authentication.

### Frontend

- **React/Vue** (or another framework): For building dynamic and responsive user interfaces.
- **Vite**: Fast build tool for frontend development.
- **CSS/SCSS**: For styling.

## Folder Structure

### Backend

- **controllers/**: Business logic for routes.
- **middleware/**: Functions to handle request pre-processing.
- **models/**: Database schemas and models.
- **routes/**: Defines API endpoints.
- **utils/**: Utility functions.
- **server.js**: Entry point for the backend server.

### Frontend

- **public/**: Static assets.
- **src/**: Source code, including components, hooks, and styles.
- **index.html**: Entry point for the application.
- **vite.config.js**: Configuration for Vite.

## Installation and Setup

### Prerequisites

- Node.js and npm/yarn installed.
- MongoDB database running.

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/gigzy-fullstack.git
   ```
2. **Navigate to the backend folder and install dependencies:**
   ```bash
   cd backend
   yarn install # or npm install
   ```
3. **Set up environment variables:**
   - Create a `.env` file in the backend folder with the following keys:
     ```env
     MONGO_URI=your-mongodb-uri
     JWT_SECRET=your-secret-key
     PORT=5000
     ```
4. **Start the backend server:**
   ```bash
   yarn start # or npm start
   ```
5. **Navigate to the frontend folder and install dependencies:**
   ```bash
   cd ../frontend
   yarn install # or npm install
   ```
6. **Start the frontend development server:**
   ```bash
   yarn dev # or npm run dev
   ```
7. **Access the application:**
   - Frontend: `http://localhost:3000`
   - Backend API: `http://localhost:5000`

## Contributing

Contributions are welcome! Please fork the repository, create a new branch for your feature or bug fix, and submit a pull request.

---

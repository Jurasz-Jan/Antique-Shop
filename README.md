# Antique Shop

A web application for managing an antique shop using a full-stack JavaScript stack. The project utilizes MongoDB for database management, React for the frontend, Express.js for the backend API, and Node.js as the runtime environment.

## Tech Stack
- **MongoDB**: NoSQL database for storing data.
- **React**: Frontend library for building the user interface.
- **Express.js**: Backend framework for handling API requests.
- **Node.js**: Server-side runtime environment.

## Setting Up Your Own MongoDB Cluster
To run the project locally, you need to set up your own MongoDB cluster. Follow these steps:
1. **Create a Free MongoDB Cluster**:
   - Go to [MongoDB Cloud](https://cloud.mongodb.com).
   - Sign up and create a free cluster.

2. **Update Connection String**:
   - Navigate to the `backend/config.js` file in your project.
   - Replace the `mongoURI` variable with your MongoDB connection string.

## Running the Application

### Backend
1. Open a terminal window and navigate to the backend directory:
   ```bash
   cd backend

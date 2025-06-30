# HouseHunt - Finding Your Perfect Rental Home

HouseHunt is a full-stack MERN (MongoDB, Express, React, Node.js) application designed to streamline the process of finding and listing rental properties. It provides a user-friendly platform for both potential tenants and property owners.

## Features

- **User Authentication:** Secure sign-up and login functionality for users.
- **Property Listings:** Browse a comprehensive list of available rental properties.
- **Advanced Search & Filter:** Easily search for properties based on location, price, and other criteria.
- **Property Management:** Authenticated users can create, update, and delete their own property listings.
- **Detailed Property Views:** View in-depth details for each property, including images, descriptions, and amenities.

## Tech Stack

- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB with Mongoose

## Prerequisites

Before you begin, ensure you have the following installed on your local machine:
- [Node.js](https://nodejs.org/en/) (v16 or newer is recommended)
- [MongoDB](https://www.mongodb.com/try/download/community) (or a cloud-based MongoDB Atlas account)

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing.

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/househunt-finding-your-perfect-rental-home.git
cd househunt-finding-your-perfect-rental-home
```

### 2. Configure and Run the Backend Server

The backend requires a connection to a MongoDB database.

```bash
# Navigate to the backend directory
cd backend

# Install dependencies
npm install

# Create a .env file in the /backend directory and add your database connection string
# Replace the placeholder with your actual MongoDB URI
echo "MONGO_DB=mongodb://127.0.0.1:27017/househunt" > .env

# Start the server (it will run on the port specified in your code, likely 5000 or 8000)
npm start
```

### 3. Configure and Run the Frontend Client

Open a **new terminal window** for this step.

```bash
# Navigate to the frontend directory from the project root
cd client

# Install dependencies
npm install

# Start the React development server (it will open in your browser at http://localhost:3000)
npm start
```

Your application is now running! The React frontend at `http://localhost:3000` will communicate with the Express backend server.


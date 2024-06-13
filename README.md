# Food Donation Application

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
The Food Donation Application is a web-based platform designed to facilitate the donation of food to those in need. It connects donors who have surplus food with agents who can deliver the food to designated locations, coordinated by an admin. The platform ensures efficient management and distribution of food donations through a streamlined process involving multiple roles.

## Features
- **Donor Registration and Login:** Donors can register and login to the platform to donate food.
- **Admin Dashboard:** Admin can view details of donors and agents, manage donation requests, and assign agents to collect food.
- **Agent Registration and Login:** Agents can register and login to the platform to view assigned donation pickups.
- **Donation Requests:** Donors can send donation requests to the admin.
- **Request Management:** Admin can accept donation requests and assign them to available agents.
- **Notifications:** Agents receive notifications about assigned pickups.

## Technologies Used
- **Frontend:**
  - React.js
  - HTML5
  - CSS3
  - Bootstrap
- **Backend:**
  - Node.js
  - Express.js
- **Database:**
  - MongoDB
- **Authentication:**
  - JSON Web Tokens (JWT)
- **Other Tools:**
  - Mongoose
  - Axios

## Installation
To get a local copy up and running, follow these steps:

1. Clone the repository:
   ```sh
   https://github.com/praneethramisetti168/FOOD-DONATION.git  
   ```

2. Navigate to the project directory:
   ```sh
   cd food-donation-app
   ```

3. Install backend dependencies:
   ```sh
   cd backend
   npm install
   ```

4. Install frontend dependencies:
   ```sh
   cd ../frontend
   npm install
   ```

5. Set up environment variables:
   - Create a `.env` file in the `backend` directory and add the following:
     ```
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

## Usage
1. Start the backend server:
   ```sh
   cd backend
   npm start
   ```

2. Start the frontend development server:
   ```sh
   cd ../frontend
   npm start
   ```

3. Open your browser and navigate to `http://localhost:3000`.

### User Roles and Flow:
- **Donor:**
  1. Register and login.
  2. Send a donation request with food details to the admin.
  3. Wait for confirmation and further instructions from the admin.

- **Admin:**
  1. Login to the admin dashboard.
  2. View donation requests from donors.
  3. Accept requests and assign them to available agents.
  4. Monitor the status of donations

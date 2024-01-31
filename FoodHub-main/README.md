# FoodHub - MERN Stack Website

FoodHub is a full-stack web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to discover and order various food items listed by FoodHub.


## Features

- ### User Registration and Authentication:
  Users can sign up and log in to the application to access their personalized account.

- ### Food Menu:
  Menu, showcasing the available food items and their prices.

- ### Cart Functionality: 
  Users can add or remove food items from their cart as per their requirements.

- ### Order Placement:
  Users can place orders, specifying the desired items and quantities.  

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/your-username/foodhub.git
   ```

2. Navigate to the project directory:

   ```
   cd foodhub
   ```

3. Install the dependencies for both the backend and frontend:

   ```
   cd backend && npm install
   ```
   ```
   cd ../frontend && npm install
   ```

4. Set up environment variables:

  - Create a .env file in the backend directory.
  - Add the following variables to the .env file:

     ```
     PORT=5000
     MONGO_URI=<your-mongodb-connection-string>
     JWT_SECRET=<your-jwt-secret>
     ```

5. Start the backend server:

   ```
   cd backend && npm start
   ```

5. Start the frontend development server:

   ```
   cd frontend && npm start
   ```

6. Access the application by visiting `http://localhost:3000` in your web browser.


## Technologies Used

- ### Backend:
 - Node.js
 - Express.js
 - Postman
 - MongoDB (with Mongoose)
 - JWT (JSON Web Tokens) for authentication

- ### Frontend:
 - React.js
 - Redux (for state management)
 - Axios (for API requests)
 - React Router (for routing)
 - Material-UI (for UI components)





# PIZZA-EXPRESS

Table of Contents
Introduction
Features
Tech Stack
Installation
Usage
Contributing
License
Introduction
Pizza Express is a full stack web application designed to streamline the process of ordering and delivering pizzas. It offers an intuitive user interface for customers to place orders, track delivery status, and manage their profiles. The project also includes an admin panel for managing orders, pizzas, and delivery personnel.

Features
User authentication and profile management
Browse and search for pizzas
Add and customize pizza orders
Real-time order tracking
Admin panel for managing orders, pizzas, and delivery personnel
Responsive design for seamless usage across devices
Tech Stack
Frontend:
HTML, CSS, JavaScript
React.js
Backend:
Node.js, Express.js
MongoDB (for database)
Other:
JWT for authentication
Redux for state management
Axios for API calls
Installation
Prerequisites
Node.js and npm installed
MongoDB installed and running
Steps
Clone the repository:

bash
Copy code
git clone https://github.com/piyusha2001/OIBSIP_Pizza-delivery-app.git
cd OIBSIP_Pizza-delivery-app
Install dependencies for the server and client:

bash
Copy code
# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
Set up environment variables:
Create a .env file in the server directory and add the following:

env
Copy code
MONGO_URI=<your_mongodb_uri>
JWT_SECRET=<your_jwt_secret>
Start the development servers:

bash
Copy code
# Start the backend server
cd server
npm start

# Start the frontend development server
cd ../client
npm start
Usage
Open your browser and navigate to http://localhost:3000 to view the application.
Register or log in to your account.
Browse the menu, customize your pizza, and place an order.
Track your order status in real-time.
Contributing
We welcome contributions to Pizza Express! To contribute:

Fork the repository.
Create a new branch: git checkout -b feature/YourFeature.
Make your changes and commit them: git commit -m 'Add some feature'.
Push to the branch: git push origin feature/YourFeature.
Submit a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

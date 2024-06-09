# MERN E-commerce Website

This project is an e-commerce website built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to browse products, add them to the cart, and make purchases.

## Features

1. **Product Catalog**: Browse a wide range of products with detailed descriptions.
2. **User Authentication**: Secure user authentication and authorization system.
3. **Shopping Cart**: Add products to the cart and proceed to checkout.
4. **Payment Integration**: Integrated payment gateway for seamless transactions.
5. **Order Tracking**: Track the status of orders from purchase to delivery.
6. **Admin Panel**: Manage products, orders, and users through an admin dashboard.

## Technologies Used

- **Frontend**: React.js, Redux, HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js, MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Payment**: Razorpay API

## Getting Started

Follow these steps to set up and run the project locally.

### Step 1: Clone the repository

```sh
git clone https://github.com/your-username/mern-ecommerce.git
cd mern-ecommerce
```

###  Step 2: Install dependencies
```sh
cd frontend
npm install
cd ../backend
npm install
```
### Step 3: Set up environment variables

Create a .env file in the backend directory and add the following environment variables:

```sh
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PASSWORD=your_database_password
TEST_EMAIL=your_test_email_address
TEST_PASS=your_test_email_password
PORT=3000
```

### Step 4: Run the development server

```sh
cd backend
npm start
```

Open another terminal:

```sh
cd frontend
npm start
```

### Step 5: Explore the website

Open your browser and go to http://localhost:3000 to explore the e-commerce website.




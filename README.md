# Shopease

**Shopease** is an online e-commerce platform that allows users to browse products, add items to their cart, and complete purchases through a simple and user-friendly interface. Built using the MERN stack, Shopease is designed to provide a seamless shopping experience for users, featuring authentication, product management, and a shopping cart system.

## Features

- **User Authentication**: Users can create an account, log in, and manage their profile.
- **Product Catalog**: Browse a variety of products, each with detailed descriptions.
- **Shopping Cart**: Add and remove items from the cart, with real-time updates.
- **Checkout Process**: Complete purchases, review order summary, and proceed to payment.
- **Backend Integration**: Robust backend using Node.js, Express.js, and MongoDB Atlas for secure data storage.

## Tech Stack

- **Front-End**: React.js
- **Back-End**: Node.js, Express.js
- **Database**: MongoDB Atlas
- **Authentication**: JWT (JSON Web Tokens)
- **Payment Integration**: In-progress

## Getting Started

### Prerequisites

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/en/) (v14 or higher)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/deborahambelo/shopease.git
   cd shopease
   ```

2. Install the dependencies for both the client and server:

   ```bash
   npm install
   cd client
   npm install
   ```

3. Set up the environment variables:

   - Create a `.env` file in the root of the project and add the following:

     ```bash
     MONGO_URI=your_mongo_db_connection_string
     JWT_SECRET=your_jwt_secret_key
     ```

4. Start the development servers:

   - To run both the client and server concurrently:

     ```bash
     npm run dev
     ```

   The React client will run on `http://localhost:3000`, and the Node.js API will run on `http://localhost:5000`.

## Usage

Once the application is running, users can:

- Register or log in to their account.
- Browse available products.
- Add or remove items from the shopping cart.
- Proceed to checkout (payment integration is still in progress).

## Project Status

- **User authentication**: Complete
- **Product browsing and cart**: Complete
- **Checkout process**: Complete (except for payment integration)
- **Payment system**: In-progress

## Future Enhancements

- Complete the integration of a payment gateway (Stripe/PayPal).
- Add a product search and filtering feature.
- Implement user order history and reviews.
- Improve product recommendation algorithms.

## Contributing

If you'd like to contribute, feel free to submit a pull request or open an issue. Contributions are welcome!

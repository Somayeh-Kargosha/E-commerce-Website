# E-commerce-Website

This is an E-commerce website project developed using [Angular](https://angular.io/) and [Node.js](https://nodejs.org/). It provides a platform for users to browse and purchase products online.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Features

- User authentication: Sign up and login functionality for users.
- Product listing: Display a list of available products with details such as name, price, and description.
- Product search: Search functionality to find specific products.
- Product filtering: Filter products based on categories, price range, and other attributes.
- Shopping cart: Add products to a shopping cart, modify quantities, and proceed to checkout.
- Order placement: Place orders for selected products and receive order confirmation.
- Payment integration: Integration with a payment gateway for secure online transactions.
- User profiles: Allow users to create and update their profiles with personal information and preferences.
- Admin panel: Admin interface to manage products, users, orders, and other aspects of the website.
- Order tracking: Enable users to track the status of their orders.
- Wishlist: Users can save products to a wishlist for future reference.
- Reviews and ratings: Allow users to leave reviews and ratings for products.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Somayeh-Kargosha/E-commerce-Website.git

   ```

2. Navigate to the project directory:

   ```bash
   cd E-commerce-Website

   ```

3. Install the dependencies:

   ```bash
   npm install

   ```

4. Set up environment variables:

- Create a `.env` file in the root directory.
- Specify the required environment variables in the `.env` file. For example:

   ```markfile
   PORT=3000
   DATABASE_URL=mongodb://localhost/e_commerce
   SECRET_KEY=mysecretkey

   ```
5. Start the development server:

   ```bash
   npm start
   ```

6.Open your web browser and visit http://localhost:3000 to access the website.

## Usage

- Register a new user account or log in with existing credentials.
- Browse products by navigating through different categories or using the search functionality.
- Add desired products to the shopping cart.
- View and modify the contents of the shopping cart.
- Proceed to checkout to place an order.
- Make a payment using the integrated payment gateway.
- Track the status of your orders.
- Explore user profiles, wishlists, and other personalized features.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Implement your changes.
4. Write appropriate tests.
5. Ensure all tests pass.
6. Commit your changes and push to your forked repository.
7. Create a new pull request with a detailed description of your changes.

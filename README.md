# E-Commerce Site

A full-stack e-commerce application developed as an academic project. This site features product search, cart management, payment processing, user authentication, and admin functionalities. Built with React, Express, and MongoDB, it showcases comprehensive full-stack development skills.

## Features

- **Product Search**: Find products easily.
- **Cart Management**: Add items to your cart and proceed to checkout.
- **Payment Processing**: Securely pay for items.
- **User Authentication**: Sign in, sign up, and manage user accounts.
- **Admin Functionalities**: Add new admins, manage products, and view all orders.

Install Dependencies (frontend & backend)
npm install
cd frontend
npm install
Run

# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
Build & Deploy
# Create frontend prod build
cd frontend
npm run build
Seed Database
You can use the following commands to seed the database with some sample users and products as well as destroy all data

# Import data
npm run data:import

# Destroy data
npm run data:destroy
Sample User Logins

admin@email.com (Admin)
123456

john@email.com (Customer)
123456

jane@email.com (Customer)
123456

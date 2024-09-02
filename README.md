## About the project
This project is an online shopping cart system that allows users to browse products, add items to their shopping cart, and complete orders with secure payment processing. It supports user authentication, dynamic product management, and real-time updates to the shopping cart and order statuses. The backend is implemented in Java, while Oracle SQL is used for database management.

## Features
User Authentication: Secure registration and login functionality.
Product Management: Admin users can add, update, and remove products from the catalog.
Cart Operations: Users can add, remove, and adjust quantities of items in their cart.
Order Processing: Complete checkout process with order summary and payment handling.
Database Integration: All data is stored and managed using Oracle SQL.
Error Handling and Validation: Comprehensive input validation and error handling.

## Usage
Launch the Application: Start the application using your IDE or command line.
Register or Log In: Create a new user account or log in with an existing one.
Browse Products: View available products, filter by category, and search for specific items.
Add to Cart: Add items to your cart and adjust quantities as needed.
Checkout: Proceed to checkout, provide necessary payment details, and confirm your order.
Admin Operations: If logged in as an admin, manage product listings and view order histories.

## Database Schema
The application uses an Oracle SQL database to store user data, product listings, orders, and payment information. Below is a brief overview of the main tables:
Users: Stores user information (ID, username, password, email, etc).
Products: Contains product details (ID, name, description, price, stock, etc).
Orders: Keeps track of user orders (order ID, user ID, date, status, total amount).
Order_Items: Details of items in each order (order ID, product ID, quantity, subtotal).

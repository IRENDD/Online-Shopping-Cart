## About the project
The Online Shopping Cart project is a full-featured platform that allows users to browse products, add them to their cart, and complete orders through a secure checkout process. This system is built to simulate a real-world e-commerce application with robust back-end and CLI, enabling user management, product handling, and transaction processing.

## Features
1. User Authentication: Secure registration and login functionality; Role-based access control (admin, customer); Profile management and order history.
2. Product Management: Admins can add, update, delete, and manage product listings; Support for product categories, descriptions, pricing, and stock levels.
3. Cart Operations: Users can add, remove, or update the quantity of items in their cart; Dynamic calculation of totals and discounts.
4. Order Processing: Complete checkout process, including payment information; Generation of order summary and confirmation; Order status tracking for users.
5. Database Integration: All data is stored and managed using Oracle SQL.
6. Error Handling and Validation: Comprehensive input validation and error handling.

## Usage
1. Launch the Application: Start the application using your IDE or command line.
2. Register or Log In: Create a new user account or log in with an existing one.
3. Browse Products: View available products, filter by category, and search for specific items.
4. Add to Cart: Add items to your cart and adjust quantities as needed.
5. Checkout: Proceed to checkout, provide necessary payment details, and confirm your order.
6. Admin Operations: If logged in as an admin, manage product listings and view order histories.

## Database Schema
The application uses an Oracle SQL database to store user data, product listings, orders, and payment information. Below is a brief overview of the main tables:
1. Users: Stores user information (ID, username, password, email, etc).
2. Products: Contains product details (ID, name, description, price, stock, etc).
3. Orders: Keeps track of user orders (order ID, user ID, date, status, total amount).
4. Order_Items: Details of items in each order (order ID, product ID, quantity, subtotal).

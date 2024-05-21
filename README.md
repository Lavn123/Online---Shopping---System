# Online---Shopping---System
## Introduction

I have developed a comprehensive online shopping system that integrates a Database Management System (DBMS) with a dynamic frontend built using HTML, CSS, and JavaScript. This system provides users with a seamless and intuitive interface to browse, search, and purchase products online. The backend is powered by a robust DBMS that handles all data storage and management tasks, ensuring efficient and secure processing of user information, product details, and order transactions.

## Working

### 1. User Registration and Authentication
   - **Registration**: New users can create an account by filling out a registration form. Their details, such as name, email, password, and address, are securely stored in the `users` table of the database.
   - **Login**: Registered users can log in using their credentials. The system verifies the provided details against the records in the `users` table to authenticate the user.

### 2. Product Browsing and Searching
   - Product Listing: Users can browse through a catalog of products retrieved from the `products` table in the database. The product listing page displays essential details such as product name, description, 
      price, and stock availability.
   - Search Functionality: Users can search for specific products using keywords. The system queries the `products` table to find and display matching items.

### 3. Shopping Cart Management
   - Add to Cart: Users can add products to their shopping cart. Each addition updates the `cart` table in the database with the user's ID, product ID, and the quantity selected.
   - View Cart: Users can view the contents of their shopping cart at any time. The cart page shows all the items added, along with options to update quantities or remove items.

### 4. Order Placement and Processing
   - Checkout: Users proceed to checkout, where they review their order details, provide shipping information, and confirm the purchase.
   - Order Confirmation: Upon confirmation, the order details are stored in the `orders` table, and the stock quantity in the `products` table is updated. Users receive an order confirmation, and the system updates the order status.

### 5. Admin Panel
   - Product Management: Admins have access to a control panel where they can add new products, update existing product details, or remove products from the catalog. These operations are reflected in the `products` table.
   - Order Management: Admins can view all orders, update their status (e.g., processing, shipped, delivered), and handle user queries related to orders.

## Technical Implementation

### Database Schema
  - Users Table: Stores user details such as user ID, name, email, password, and address.
  - Products Table: Stores product details including product ID, name, description, price, stock quantity, and category.
  - Orders Table: Stores order details like order ID, user ID, total amount, order status, and order date.
  - Cart Table: Temporarily stores data of the products added to the user's shopping cart, including user ID, product ID, and quantity.

### Frontend
  - HTML: Defines the structure of the web pages, including forms for user registration, login, product listings, and the shopping cart.
  - CSS: Styles the web pages to ensure a consistent and user-friendly interface.
  - JavaScript: Adds interactivity to the web pages, such as handling form submissions, updating the shopping cart, and making AJAX requests to communicate with the backend.

### Conclusion

The implemented online shopping system provides a complete solution for online retail operations. It ensures a smooth user experience through a well-designed frontend while maintaining data integrity and security with a robust backend database. This system is scalable and can be extended with additional features like payment gateway integration, user reviews, and advanced search filters to enhance functionality and user satisfaction.

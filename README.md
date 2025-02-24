# Restaurant Database Management System

## Overview
This project is a relational database system for managing restaurant operations. It includes multiple tables to store and manage data related to restaurants, customers, orders, food, chefs, waiters, and billing. The database is structured using SQL with appropriate relationships and constraints.

## Features
- **Restaurant Management**: Stores restaurant details including names and contact numbers.
- **Customer Management**: Keeps track of customers, their contact details, and their preferred restaurants.
- **Order Handling**: Records orders, food items, and their quantities.
- **Waiter & Chef Tracking**: Links orders to waiters and chefs for better management.
- **Billing System**: Stores bill details, including prices, VAT, and customer payments.
- **Food Details**: Maintains food descriptions, pricing, and availability.

## Database Schema
The database consists of the following tables:
1. `resturnt` - Stores restaurant details.
2. `customer` - Contains customer information linked to restaurants.
3. `restaurant_info` - Stores additional details about restaurants.
4. `waiter` - Tracks waiters assigned to customers and orders.
5. `orderr` - Manages orders and their item counts.
6. `order_info` - Contains order processing time.
7. `food` - Stores food item details.
8. `food_details` - Includes food pricing and quantity.
9. `chef` - Tracks chefs responsible for specific orders.
10. `bill` - Stores billing details for customer orders.
11. `bill_dtls` - Includes VAT calculations on food items.

## SQL Queries
The project includes useful SQL queries for:
- Displaying ordered foods and their order numbers.
- Retrieving waiter names who took specific orders.
- Listing customer names, contact details, and restaurant names.
- Finding customers who visited specific restaurants.
- Displaying customer names for specific food orders.

## Setup Instructions
1. **Database Creation**
   - Run the SQL script to create the `RESTAURANT` database.
   - Execute table creation queries.
   - Insert sample data into tables.

2. **Executing Queries**
   - Use the provided SQL queries to extract useful insights.

3. **Modifications & Customization**
   - You can modify the database schema to fit additional requirements.
   - Extend queries for better data analysis and reporting.

## Technologies Used
- **SQL** (Structured Query Language)
- **MySQL** or any relational database management system (RDBMS)

## License
This project is open-source and free to use for learning and educational purposes.

## Author
[M. Amir Ali Asif]

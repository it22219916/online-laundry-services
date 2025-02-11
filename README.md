# Laundry Management System

## Overview

The Laundry Management System is a web application designed to streamline the process of managing laundry services. It provides functionalities for both customers and administrators, allowing customers to place orders and administrators to manage those orders efficiently.

## Features

### Customer Features

- **User Registration and Login**: Customers can register and log in to their accounts.
- **Place Orders**: Customers can place orders for various laundry services such as washing, ironing, and dry cleaning.
- **Order Tracking**: Customers can track the status of their orders.
- **Profile Management**: Customers can update their profile information.
- **Contact Us**: Customers can send inquiries or feedback through the contact form.

### Admin Features

- **Admin Dashboard**: Administrators can view and manage all customer orders.
- **Employee Management**: Administrators can add, update, and delete employee information.
- **Contact Management**: Administrators can view and respond to customer inquiries.
- **Order Management**: Administrators can update the status of customer orders.

## Installation

1. **Install a Local Server Environment**:

   - Install a local server environment like XAMPP, WAMP, or MAMP. These packages include Apache, MySQL, and PHP.

2. **Start the Server**:

   - Start the Apache and MySQL services from the control panel of your local server environment.

3. **Place the Project in the Server Directory**:

   - Move your project directory (`Laundry-management-system`) to the `htdocs` directory (for XAMPP) or the equivalent directory for your server environment.

4. **Create a Database**:

   - Open phpMyAdmin (usually accessible at `http://localhost/phpmyadmin`).
   - Create a new database (e.g., `laundry_db`).
   - Import the database schema if you have a `.sql` file. Use the Import tab in phpMyAdmin to upload and execute the SQL file.

5. **Configure Database Connection**:

   - Update the database connection settings in your project files. Typically, this will be in a configuration file like `config.php` or similar.
   - Ensure the database host, username, password, and database name are correctly set.

6. **Access the Project in the Browser**:
   - Open your web browser and navigate to `http://localhost/Laundry-management-system/CUSTOMER/home.php`.

## Usage

### Customer

1. Register or log in to your account.
2. Place an order for the desired laundry service.
3. Track the status of your order.
4. Update your profile information if needed.
5. Use the contact form to send inquiries or feedback.

### Admin

1. Log in to the admin dashboard.
2. View and manage customer orders.
3. Add, update, or delete employee information.
4. Respond to customer inquiries through the contact management system.
5. Update the status of customer orders.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

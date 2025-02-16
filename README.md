# PHP Inventory Management System

## Overview
This is a PHP-based Inventory Management System designed to help businesses manage stock, track sales, and monitor inventory levels efficiently. The system includes features like product management, user authentication, reports, and more.

## Features
- User authentication (Admin & Staff roles)
- Product management (Add, Edit, Delete, and View)
- Stock tracking and updates
- Sales and purchase management
- Supplier and customer management
- Reports generation
- Responsive design for accessibility

## Requirements
To run this project, ensure your system meets the following requirements:
- XAMPP/WAMP Server (PHP 7.4+)
- MySQL Database
- Apache Server
- Web browser (Chrome, Firefox, Edge, etc.)

## Installation
1. **Download and Extract**
   - Download the project and extract the files into the `htdocs` folder (for XAMPP) or `www` folder (for WAMP).

2. **Database Setup**
   - Open `phpMyAdmin` and create a new database (e.g., `inventory_db`).
   - Import the provided SQL file (`inventory_db.sql`) into the newly created database.

3. **Configure Database Connection**
   - Open `config.php` in the project folder.
   - Update the database credentials:
     ```php
     $servername = "localhost";
     $username = "root";
     $password = "";
     $dbname = "inventory_db";
     ```

4. **Run the Application**
   - Start Apache and MySQL from XAMPP/WAMP.
   - Open a browser and go to: `http://localhost/inventory-management-system/`

## Usage
- **Admin Login:** Use default admin credentials (can be changed in the database).
- **Manage Products:** Add, update, or delete inventory items.
- **Track Stock:** Monitor product levels and get notifications for low stock.
- **Generate Reports:** View sales, stock, and supplier reports.

## Troubleshooting
- If you see a database connection error, ensure MySQL is running and that your database credentials are correct.
- If styles or scripts do not load correctly, check your Apache server settings.

## Contribution
Feel free to contribute by submitting pull requests or reporting issues.

## License
This project is licensed under the MIT License.


# Project_PHP_E-commerce_App
Project Description: Online E-commerce Shop Development
Overview
This project involves the creation of a commercial, transactional web application utilizing PHP and MySQL technologies. The core functionality revolves around an online e-commerce shop that allows users to explore a variety of products, add selections to a shopping cart, and proceed with order placements. Although the project will simulate the shopping and order process, it will not incorporate an actual payment transaction system.

Design Freedom and Product Offerings
Participants are granted the liberty to decide on the shop's overall design, theme, and the range of products available for sale, with the requirement that the store must offer at least six different products.

Development Timeline
The development phase is scheduled between weeks 5 to 14 of the semester, following a structured timeline that includes:

Setting up the directory structure and webpage layouts.
Creating database structures and MySQLi query functions.
Transitioning from MySQLi to PDO for database interaction.
Implementing PHP sessions and developing web page HTML and forms.
Connecting HTML forms to PHP through AJAX and finalizing data validation and business logic.
Project Requirements
Technical Requirements
The application must be built in PHP and designed for execution on an Apache web server.
Data storage and retrieval must be managed using a MySQL/MariaDB database, with PDO as the PHP database connection system.
The application should be free of major execution errors.
Usage of complete large-scale frameworks is restricted; however, jQuery and Bootstrap are permitted for front-end development.
The final submission must include the database exported as an SQL script within a ZIP archive, alongside the project directory.
Functional Requirements
The application should be a single-page application encompassing:

User registration and login, with redirection to the product page upon successful login.
A dynamic product listing page with product details and the ability to add products to the shopping cart.
A shopping cart page for viewing and modifying cart contents, including subtotal display.
An order page for reviewing the cart, entering addresses, calculating the order total, and placing an order.
An order confirmation page for reviewing placed orders.
Object Modelization
The project must model and store representations of the following entities within the database:

Customer (ID, username, password hash, creation date)
Product (ID, name, description, image URL, price, quantity, creation date)
Shopping Cart (ID, status, creation date)
ShoppingCartProduct (product ID, cart ID, quantity)
Order (ID, status, customer ID, cart ID, billing and shipping addresses, creation dates)
Conclusion
This project aims to provide hands-on experience in developing a fully functional e-commerce platform, emphasizing PHP and MySQL for backend development, without relying on large-scale frameworks or pre-written code. Through this project, participants will gain practical skills in web development, database management, and application design within a real-world context.

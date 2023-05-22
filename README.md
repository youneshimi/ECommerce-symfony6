# Backoffice E-commerce Application

This project is a backoffice e-commerce application that allows administrators of an e-commerce website to manage their daily business operations online. It provides a secure web interface accessible only with specific login credentials. The main features of our backoffice e-commerce application include:

- Product Management: Ability to add, modify, and delete products, set prices, add images and descriptions, and manage product categories.
- Order Management: Ability to view and manage all orders placed on the e-commerce website, including product details, customer information, payments, and shipments.
- Customer Management: Ability to create and manage customer accounts, track purchase history, manage shopping carts, and respond to customer inquiries.
- Promotion and Discount Management: Ability to create and manage promotion codes, discounts, and special offers to attract and retain customers.

The application is developed using the Symfony framework and associated technologies such as Doctrine for the ORM (Object-Relational Mapping) and Twig for views. It leverages the power of PHP and provides a robust and scalable solution for managing e-commerce operations.

## Getting Started

To get started with the application, follow these steps:

1. Clone the repository to your local machine.
2. Install the necessary dependencies by running `composer install` in the project root directory.
3. Configure the database connection in the `.env` file with your MySQL credentials.
4. Create the database by running `php bin/console doctrine:database:create`.
5. Generate the required database schema by running `php bin/console doctrine:schema:update -f`.
6. Launch the Symfony development server with `symfony server:start -d`.
7. Access the application in your browser at `http://localhost:8000`.

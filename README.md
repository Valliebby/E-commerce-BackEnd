# E-commerce-BackEnd

E-commerce Back End - Object-Relational Mapping (ORM)
This repository contains the code for an E-commerce Back End application using Object-Relational Mapping (ORM) to interact with a relational database. The application is built to handle the backend operations of an online store, such as managing products, categories, and tags.

Table of Contents
Introduction
Requirements
Getting Started
Database
ORM
API Endpoints
Error Handling
Contributing
License
Introduction
This application provides the back end for an E-commerce platform. It is built using Node.js and utilizes ORM techniques to interact with a relational database. With this back end, you can manage products, categories, and tags, which can be used to power an E-commerce website or application.

Requirements
Before running the application, make sure you have the following installed:

Node.js (https://nodejs.org/)
MySQL database (https://www.mysql.com/)
Getting Started
Clone the repository and navigate to the project directory.

Install the dependencies using npm:

Copy code: git clone https://github.com/Valliebby/E-commerce-BackEnd
npm install
Create a .env file in the root directory and set the following environment variables:

env
Copy code
DB_USER=<your_database_user>
DB_PASSWORD=<your_database_password>
DB_NAME=<your_database_name>
DB_HOST=<your_database_host> # Usually 'localhost' if running the database locally
DB_PORT=<your_database_port> # Default is 3306 for MySQL
Import the provided database schema and seed data into your MySQL database. You can find the SQL file in the db folder.

Start the server:

npm start
The API will be available at http://localhost:3001 by default. You can change the port by modifying the PORT environment variable in the .env file.

Database
The application uses a MySQL database to store and manage the E-commerce data. The database schema includes three main tables:

products: Contains information about the products available in the E-commerce store, including product names, prices, stock quantities, and references to the corresponding categories and tags.

categories: Represents the product categories, such as electronics, clothing, or accessories.

tags: Stores various tags associated with products, such as "new," "on sale," or "limited edition."

ORM
The application uses an ORM (Object-Relational Mapping) technique to interact with the MySQL database. The ORM library simplifies the database queries and data manipulation by converting JavaScript objects into database records and vice versa.

API Endpoints
The following are the available API endpoints:

GET /api/products: Fetch all products with their associated category and tag information.

GET /api/products/:id Fetch a specific product by its ID along with its associated category and tag information.

POST /api/products: Create a new product and associate it with one or more categories and tags.

PUT /api/products/:id Update an existing product by its ID.

DELETE /api/products/:id Delete a product by its ID.

GET /api/categories: Fetch all categories along with their associated products.

GET /api/categories/:id Fetch a specific category by its ID along with its associated products.

POST /api/categories: Create a new category.

PUT /api/categories/:id Update an existing category by its ID.

DELETE /api/categories/:id Delete a category by its ID.

GET /api/tags: Fetch all tags along with their associated products.

GET /api/tags/:id Fetch a specific tag by its ID along with its associated products.

POST /api/tags: Create a new tag.

PUT /api/tags/:id Update an existing tag by its ID.

DELETE /api/tags/:id Delete a tag by its ID.

Thank you and enjoy!


Get all routes:



https://github.com/Valliebby/E-commerce-BackEnd/assets/119483866/f11a6226-b660-4656-83b0-20f0270852e8


Get a single route:
[Untitled_ Jul 25, 2023 11_57 AM.webm](https://github.com/Valliebby/E-commerce-BackEnd/assets/119483866/8131559d-80b0-4e11-90c0-6e493e5148e2)

https://drive.google.com/file/d/1_fhYxvxhwvh6oEjKYr4LsZpQBeRmv4Vi/view

Delet Post [Post.webm](https://github.com/Valliebby/E-commerce-BackEnd/assets/119483866/d14464cd-b2cb-476a-8313-906d20e95827)


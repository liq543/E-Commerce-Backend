# E-Commerce Back End
## Description
This is the back end API for an e-commerce website, built using Node.js, Express, MySQL and Sequelize. It provides a RESTful API with endpoints for managing products, categories and tags in a database.

The application demonstrates creating a full CRUD API using Sequelize to interface with a MySQL database for an e-commerce site. It follows best practices for organization, error handling and asynchronous code.

# Usage
The application requires Node.js, Express, MySQL and Sequelize to be installed.

Configure the database credentials in a .env file. Import the provided SQL schema to create the database structure.

```bash
npm install
npm run seed 
npm start
The server will start on port 3001. Use an API client like Insomnia or Postman to test the API endpoints.
```

Some example endpoints:

```bash
GET /api/products
POST /api/products
PUT /api/products/1  
DELETE /api/products/1

GET /api/categories  
POST /api/categories

GET /api/tags
POST /api/tags
```

Routes

```bash
/api/products
/api/categories
/api/tags
Built With
JavaScript
Node.js
Express
MySQL
Sequelize
Dotenv
Demo
```

# Video Demo

# License
This project is licensed under the MIT license. See the LICENSE file for details.
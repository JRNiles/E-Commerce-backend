# eCommerce Backend

This project is a backend application for an eCommerce platform. It provides API endpoints for managing categories, products, and tags, as well as relationships between them.

## Table of Contents

- [eCommerce Backend](#ecommerce-backend)
  - [Table of Contents](#table-of-contents)
  - [Technologies Used](#technologies-used)
  - [Installation](#installation)
  - [Usage](#usage)
  - [API Endpoints](#api-endpoints)

## Technologies Used

- Node.js
- Express.js
- Sequelize (ORM for interacting with MySQL database)
- MySQL database

## Installation

1. **Clone the repository:**

   ```bash
   git clone <repository_url>

2. **Navigate to the project directory**
   
   ```bash 
   cd E-commerce-backend

3. **Install dependencies**
   ```bash  
   npm install

4. **Run the database migrations and seed the database**
   ```bash  
   npm run seed

5. **Start the server**
    ```bash
    npm start  

## Usage
Once the server is running, you can use an API testing tool like Insomnia or Postman to interact with the API endpoints.

## API Endpoints 
Categories:

GET /api/categories: Get all categories.

GET /api/categories/:id: Get a single category by ID.

POST /api/categories: Create a new category.

PUT /api/categories/:id: Update a category by ID.

DELETE /api/categories/:id: Delete a category by ID.

Products:

GET /api/products: Get all products.

GET /api/products/:id: Get a single product by ID.

POST /api/products: Create a new product.

PUT /api/products/:id: Update a product by ID.

DELETE /api/products/:id: Delete a product by ID.

Tags:

GET /api/tags: Get all tags.

GET /api/tags/:id: Get a single tag by ID.

POST /api/tags: Create a new tag.

PUT /api/tags/:id: Update a tag by ID.

DELETE /api/tags/:id: Delete a tag by ID.
## Node, Express, and Bootstrap eShop API
This is an API built with Node.js, Express.js, MongoDB, and Bootstrap for an eShop platform. The API provides basic CRUD functionality for users and products, and returns data in JSON format.

## Requirements
- Node.js (v10 or higher)
- MongoDB
- npm

## Technologies Used
- Express.js
- MongoDB
- Swagger
- Bootstrap

## Setup
1. Clone the repository: git clone https://github.com/g-avgeros/myEshop.git
2. Change directory: cd eshop-api
3. Install dependencies: npm install
4. Start the API: npm run dev
  
## API Endpoints
The following endpoints are available:

Users
- GET /api/users - Get all users
- GET /api/users/:id - Get a single user
- POST /api/users - Create a new user
- PUT /api/users/:id - Update an existing user
- DELETE /api/users/:id - Delete a user

Products
- GET /api/products - Get all products
- GET /api/products/:id - Get a single product
- POST /api/products - Create a new product
- PUT /api/products/:id - Update an existing product
- DELETE /api/products/:id - Delete a product

## Logging
All requests to the API are logged to the console and to MongoDB using Winston. The logs are stored in the logs collection in the eshop database.

## Documentation
API documentation is provided using Swagger. To access the documentation, go to http://localhost:3000/api-docs in your web browser.

## UI
Bootstrap is used to provide a basic UI for the API. To access the UI, go to http://localhost:3000 in your web browser.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

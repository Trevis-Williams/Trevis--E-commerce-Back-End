# Trevis E-commerce Back End

## Description
Trevis E-commerce Back End is a backend application that provides API endpoints for an e-commerce platform. It allows for operations on products, categories, and tags, enabling seamless integration with front-end e-commerce solutions.

## Video Guide 
https://drive.google.com/file/d/1CXSIZA2vw7HAw526QWFi9TjelNBs3KUu/view

## Features
- CRUD operations for managing products, categories, and tags.
- Search functionality for products by various criteria.
- Secure user authentication for admin operations.
- Integration with databases for persistent storage.

## Technologies Used
- Node.js
- Express.js for handling API requests.
- Sequelize as the ORM for database operations.
- MySQL for the relational database.
- bcrypt for hashing and securing passwords.

## Installation
To install the application, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/trevis-williams/Trevis-E-commerce-Back-End.git
   ```
2. Navigate to the cloned directory:
   ```
   cd Trevis-E-commerce-Back-End
   ```
3. Install the required npm packages:
   ```
   npm install
   ```

## Configuration
Create a `.env` file in the root directory with the following contents:
```
DB_NAME='ecommerce_db'
DB_USER='your_username'
DB_PASS='your_password'
```

## Running the Application
To start the server, run:
```
npm install
npm start
```

## API Endpoints
The following endpoints are available:

- `GET /api/products` - Retrieve all products.
- `POST /api/products` - Create a new product.
- `PUT /api/products/:id` - Update a product by its ID.
- `DELETE /api/products/:id` - Delete a product by its ID.

- `GET /api/categories` - Retrieve all categories.
- `POST /api/categories` - Create a new category.
- `PUT /api/categories/:id` - Update a category by its ID.
- `DELETE /api/categories/:id` - Delete a category by its ID.

- `GET /api/tags` - Retrieve all tags.
- `POST /api/tags` - Create a new tag.
- `PUT /api/tags/:id` - Update a tag by its ID.
- `DELETE /api/tags/:id` - Delete a tag by its ID.

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

---

Remember to replace placeholder text like `your_username`, `your_password`, and `https://github.com/your-username/Trevis-E-commerce-Back-End.git` with actual values relevant to your project. Also, this README assumes a certain set of technologies and endpoints based on typical e-commerce applications; you should adjust these to reflect the specifics of your project.


# E-Commerce Back End

## Video Example
[Video Example](https://drive.google.com/file/d/1pmBm3DIHOI-cx1AX3hZbyzHjZf-LQblO/view)

## Description
This is the back-end for an e-commerce application, providing RESTful API functionality to manage products, categories, and tags. The app uses Express.js, Sequelize ORM, and PostgreSQL to interact with the database. API routes allow for creating, reading, updating, and deleting data related to products, categories, and tags.

## Table of Contents
- [E-Commerce Back End](#e-commerce-back-end)
  - [Video Example](#video-example)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Technologies](#technologies)
  - [API Routes](#api-routes)
    - [Categories](#categories)
    - [Products](#products)
    - [Tags](#tags)
  - [License](#license)

## Installation
1. Clone the repository.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file and add the following:
   ```env
   DB_NAME=ecommerce_db
   DB_USER=your_postgres_username
   DB_PASSWORD=your_postgres_password
   DB_HOST=localhost
   DB_PORT=5432
   ```
4. Create the database using PostgreSQL.
5. Seed the database:
   ```bash
   npm run seed
   ```

## Usage
1. Start the server:
   ```bash
   npm start
   ```
2. Test the API routes using a client like **Insomnia** or **Postman**.

## Technologies
- **Node.js**
- **Express.js**
- **PostgreSQL**
- **Sequelize ORM**
- **dotenv**

## API Routes

### Categories
- `GET /api/categories`: Get all categories
- `GET /api/categories/:id`: Get category by ID
- `POST /api/categories`: Create a new category
- `PUT /api/categories/:id`: Update category by ID
- `DELETE /api/categories/:id`: Delete category by ID

### Products
- `GET /api/products`: Get all products
- `GET /api/products/:id`: Get product by ID
- `POST /api/products`: Create a new product
- `PUT /api/products/:id`: Update product by ID
- `DELETE /api/products/:id`: Delete product by ID

### Tags
- `GET /api/tags`: Get all tags
- `GET /api/tags/:id`: Get tag by ID
- `POST /api/tags`: Create a new tag
- `PUT /api/tags/:id`: Update tag by ID
- `DELETE /api/tags/:id`: Delete tag by ID

## License
MIT License.

# Chez Syarif

## Links

- Frontend Web: https://chez.syarifhasibuan.com
- Backend API: https://chez-api.syarifhasibuan.com

Repositories:

- General: https://github.com/syarifhasibuan/chez-syarif
- Frontend Web: https://github.com/syarifhasibuan/chez-syarif-frontend
- Backend API: https://github.com/syarifhasibuan/chez-syarif-backend

Inspirations:

- https://paul.fr
- https://paul-indonesia.co.id

## Features

- Home
  - Hero
  - Featured Selections
- Products List
  - Product Item
    - Images
    - Name
    - Price
    - SKU
    - Add to Cart
    - Description
    - Stock Quantity
- Product Categories
  - Breads
  - Pastries
  - Mini-Pastries
  - Beverages
  - Sandwiches
- Authentication/Authorization
  - Sign Up
  - Log In
  - Log Out
- Shopping Cart
- Checkout
  - Shipping Address

## UI Design

Figma: ...

## Entity Relationship Diagram (ERD)

![ERD](diagrams/erd.svg)

## REST API Endpoints

Products: `/products`

| Method | Path     | Description           | Status         |
| ------ | -------- | --------------------- | -------------- |
| GET    | `/`      | Get all products      | 200: `[]`      |
| GET    | `/:slug` | Get a product by slug | 200: `{}`, 404 |

Categories: `/categories`

| Method | Path     | Description            | Status         |
| ------ | -------- | ---------------------- | -------------- |
| GET    | `/`      | Get all categories     | 200: `[]`      |
| GET    | `/:slug` | Get a category by slug | 200: `{}`, 404 |

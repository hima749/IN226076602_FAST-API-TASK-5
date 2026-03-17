# IN226076602_FAST-API-TASK-5

The API simulates a simple online store with features such as product search, sorting, pagination, cart management, and order processing.

---

## Features Implemented

### Cart & Orders
- Add products to cart
- View cart items
- Remove items from cart
- Checkout cart and create orders
- View all orders

### Product APIs
- Search products by keyword
- Sort products by price or name
- Pagination for product listing
- Sort products by category then price
- Combined endpoint for search + sort + pagination

### Order APIs
- Search orders by customer name
- Pagination for orders list

---

## API Endpoints

### Cart
- `POST /cart/add`
- `GET /cart`
- `DELETE /cart/{product_id}`
- `POST /cart/checkout`

### Orders
- `GET /orders`
- `GET /orders/search`
- `GET /orders/page`

### Products
- `GET /products/search`
- `GET /products/sort`
- `GET /products/page`
- `GET /products/sort-by-category`
- `GET /products/browse`

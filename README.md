# goit-rdb-hw-02

Database normalization and schema design homework.

## What's inside

- Normalization from initial table to 1NF → 2NF → 3NF
- MySQL Workbench EER diagram with 4 tables:
  - `clients` — customer data
  - `orders` — order records linked to clients
  - `products` — product catalog
  - `order_items` — junction table linking orders and products with quantity

## Schema
clients (1) ──< orders (1) ──< order_items >── (1) products

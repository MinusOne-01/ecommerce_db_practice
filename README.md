# E-commerce Backend Schema (Scaffold)

A database-first backend scaffold built to practice **e-commerce data modeling** using PostgreSQL and Prisma.

This project focuses on **schema design**, not a complete running API.


## 🏗️ Overview

This repository defines the foundational database schema for an e-commerce backend.

It models core commerce concepts such as products, carts, and orders, with an emphasis on **data integrity and relationships**.

---

## 🗄️ Data Model

The schema includes tables for:

- **Product**  
  Product catalog and metadata

- **Inventory**  
  Stock tracking with:
  - `availableQty`
  - `reservedQty`

- **Cart**  
  User shopping carts

- **CartItem**  
  Items in a cart  
  Uses a composite key per `(cartId, productId)`

- **Order**  
  Placed orders

- **OrderItem**  
  Order line items with captured price at purchase time

---


## 🚧 Status

Scaffold-only project.  
API layer and business logic are not implemented yet.

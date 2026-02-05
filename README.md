# item-management-api
# Item Management REST API

This project is a simple Java Spring Boot backend application that provides a RESTful API
to manage items using in-memory storage (ArrayList).

This project was created as part of a freelance Java developer sample task.

---

## Tech Stack
- Java
- Spring Boot
- Maven

---

## Features
- Add a new item
- Get an item by ID
- Input validation
- In-memory data storage using ArrayList

---

## Item Model
Each item contains the following fields:
- id (Long)
- name (String)
- description (String)
- price (Double)

---

## API Endpoints

### 1. Add Item
**POST** `/api/items`

Request Body (JSON):
```json
{
  "name": "Laptop",
  "description": "Gaming laptop",
  "price": 75000
}

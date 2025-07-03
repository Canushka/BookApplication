# 📚 Book Management REST API

A simple Spring Boot project for managing books using a RESTful architecture. Includes full CRUD functionality, uses H2 in-memory database, and has been tested with Postman.

---

## 🚀 Tech Stack

- **Java 17**
- **Spring Boot 3.5**
- **Spring Data JPA**
- **H2 Database**
- **Postman**
- **Maven**

---

## 📌 Features

- ➕ Add new books
- 🔍 Get books by title
- 📝 Update book information
- ❌ Delete books by ID
- 📋 Auto database management using JPA Repository
- 💾 Test APIs using Postman
- 🖥️ View database in browser using H2 Console

---

## 🛠️ API Endpoints

| Method | Endpoint                         | Description              |
|--------|----------------------------------|--------------------------|
| POST   | `/book/v1/addBook`               | Add a new book           |
| GET    | `/book/v1/getBook/{bookName}`    | Get a book by its title  |
| PUT    | `/book/v1/updateBook`            | Update a book            |
| DELETE | `/book/v1/deleteBook/{id}`       | Delete a book by ID      |

---

## 📥 Sample JSON

```json
{
  "id": 1,
  "title": "The Alchemist",
  "author": "Paulo Coelho",
  "price": 399
}

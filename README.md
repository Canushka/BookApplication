# 📚 BookApplication

A simple Book Management REST API built using Java, Spring Boot, and H2 Database.

## 🔧 Tech Stack
- Java
- Spring Boot
- Spring Data JPA
- H2 In-Memory DB
- Maven
- Postman

## 🚀 Features
- Add a book
- Get a book by title
- Update book details
- Delete a book

## 🛠️ Endpoints

| Method | Endpoint               | Description         |
|--------|------------------------|---------------------|
| POST   | `/book/v1/addBook`     | Add a new book      |
| GET    | `/book/v1/getBook/{title}` | Get book by title   |
| PUT    | `/book/v1/updateBook`  | Update a book       |
| DELETE | `/book/v1/deleteBook/{id}` | Delete a book by ID |

## 🧪 Testing
Tested using [Postman](https://www.postman.com/). Sample JSON for add/update:

```json
{
  "id": 1,
  "title": "The Alchemist",
  "author": "Paulo Coelho",
  "price": 299
}

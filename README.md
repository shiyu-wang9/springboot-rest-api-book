# BOOK API - Spring Boot REST Project
This is a simple Spring Boot REST API project for managing a collection of books. It's built as a learning project to explore Spring Boot and RESTful architecture.

## Tech Stack
- Java 21
- Spring Boot 3.4.4
- Maven
- Spring Web
- Spring Data JPA
- H2 Database (for testing)
- Postman (for API testing)

## Endpoints Summary

| Method | Endpoint              | Description             |
|--------|-----------------------|-------------------------|
| POST   | `/api/books`          | Create a new book       |
| GET    | `/api/books`          | Get all books           |
| GET    | `/api/books/{id}`     | Get a book by ID        |
| PUT    | `/api/books/{id}`     | Update a book           |
| DELETE | `/api/books/{id}`     | Delete a book by ID     |


## Example Request Body
```json
{
"title": "Clean Code",
"author": "Robert C. Martin",
"yearPublished": 2008
}
```

## Postman API Testing Screenshots
### POST - Create book
* Add the first book  
  <br>
  <img src="postman-test-screenshots/post_book1.png" alt="book1_add" width="450"/>

* Add the second book  
  <br>
  <img src="postman-test-screenshots/post_book2.png" alt="book2_add" width="450"/>

---

### GET - Retrieve book

* Get all books  
  <br>
  <img src="postman-test-screenshots/get_all_books.png" alt="all_books" width="450"/>

* Get book by id  
  <br>
  <img src="postman-test-screenshots/get_book_by_id.png" alt="get_book_by_id" width="450"/>

---

### PUT - Update book

* Update the first book  
  <br>
  <img src="postman-test-screenshots/put_book1.png" alt="update_book1" width="450"/>

* View book 1 after updating  
  <br>
  <img src="postman-test-screenshots/get_book1_after_put.png" alt="view_updated_book1" width="450"/>

---

### DELETE - Delete book

* Delete book  
  <br>
  <img src="postman-test-screenshots/delete_book_1.png" alt="delete_book" width="450"/>
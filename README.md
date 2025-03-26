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
![book1_add](postman-test-screenshots/post_book1.png)
* Add the second book
![book2_add](postman-test-screenshots/post_book2.png)

### GET - Retrieve book
* Get all books
![all_books](postman-test-screenshots/get_all_books.png)
* Get book by id
![get_book_by_id](postman-test-screenshots/get_book_by_id.png)

### PUT - Update book
* Update the first book
![update_book1](postman-test-screenshots/put_book1.png)
* View book 1 after updating
![view_updated_book1](postman-test-screenshots/get_book1_after_put.png)

### DELETE - Delete book
* Delete book
![delete_book](postman-test-screenshots/delete_book_1.png)
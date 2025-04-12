# Spring Data Pageable Example

This is a sample Spring Boot project that demonstrates how to implement pagination and sorting using Spring Data JPA's `Pageable` interface.

## 🚀 Features

- List entities with pagination
- Sort results by any field
- Search with pagination (e.g., by author)
- Clean REST API structure
- Easily extendable for other use cases

## 📚 Use Case

The example uses a simple `Book` entity with fields like `title`, `author`, and `price`. It showcases how to:
- Retrieve books page by page
- Sort books by title, author, etc.
- Search for books by author name with pagination

## 🛠 Technologies Used

- Java 17+
- Spring Boot
- Spring Data JPA
- PostgreSQL
- Gradle

## ▶️ Example Endpoints

- `GET /api/books?page=0&size=5&sortBy=title`
- `GET /api/books/search?author=John&page=1&size=3`




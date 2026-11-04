# Library Management REST API

A RESTful Library Management API developed using Spring Boot for the Enterprise Application Development (EAD) module lab session.

## Technologies Used

- Java 21
- Spring Boot
- Spring Data JPA
- MySQL
- Maven
- Swagger / OpenAPI

## Database Configuration

1. Create a MySQL database named `library_db`.
2. Copy `src/main/resources/application.properties.example` and rename the copy to `application.properties`.
3. Update the database username and password with your own MySQL credentials.

**Note:** The actual `application.properties` file is excluded from this repository to protect database credentials.

## Running the Application

On Windows, open a terminal in the project directory and execute:

```powershell
.\mvnw.cmd spring-boot:run
```

The application runs at:

`http://localhost:8080`

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/books` | Get all books |
| GET | `/api/books/{id}` | Get a book by ID |
| POST | `/api/books` | Create a book |
| PUT | `/api/books/{id}` | Update a book |
| DELETE | `/api/books/{id}` | Delete a book |

## API Documentation

Swagger UI:

`http://localhost:8080/swagger-ui.html`
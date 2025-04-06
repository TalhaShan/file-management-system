# File Management System - Backend

Spring Boot backend for the File Management System.

## Project Structure

```
backend/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/filemanager/
│   │   │       ├── config/          # Configuration classes
│   │   │       ├── controller/      # REST controllers
│   │   │       ├── service/         # Business logic
│   │   │       ├── repository/      # Data access layer
│   │   │       ├── model/           # Entity classes
│   │   │       ├── dto/             # Data Transfer Objects
│   │   │       ├── security/        # Security configuration
│   │   │       └── util/            # Utility classes
│   │   └── resources/
│   │       ├── application.yml      # Main configuration
│   │       └── application-dev.yml  # Development configuration
│   └── test/                        # Test classes
└── pom.xml                          # Maven dependencies
```

## Dependencies

- Spring Boot Starter Web
- Spring Boot Starter Data JPA
- Spring Boot Starter Security
- Spring Boot Starter Validation
- PostgreSQL Driver
- AWS SDK for S3
- JWT
- Lombok
- MapStruct
- Spring Boot Starter Test

## API Endpoints

### Authentication
- POST /api/auth/login
- POST /api/auth/register
- POST /api/auth/refresh-token

### Files
- GET /api/files
- POST /api/files/upload
- GET /api/files/{fileId}
- DELETE /api/files/{fileId}
- PUT /api/files/{fileId}/share

### Users
- GET /api/users/profile
- PUT /api/users/profile
- GET /api/users/{userId}/files

## Configuration

### Database
- PostgreSQL configuration in application.yml
- Connection pool settings
- JPA/Hibernate settings

### AWS S3
- Bucket configuration
- Access credentials
- Region settings

### Security
- JWT configuration
- CORS settings
- Password encoder
- Role-based access control

## Running the Application

1. Ensure PostgreSQL is running
2. Configure application.yml with your database and AWS credentials
3. Run `mvn spring-boot:run`

## Testing

- Unit tests: `mvn test`
- Integration tests: `mvn verify`

## API Documentation

Swagger UI is available at: http://localhost:8080/swagger-ui.html 
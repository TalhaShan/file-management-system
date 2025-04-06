# File Management System

A modern file management system built with Spring Boot and React.

## Project Structure

```
file-management-system/
├── backend/                 # Spring Boot application
│   ├── src/
│   ├── pom.xml
│   └── README.md
├── frontend/               # React application
│   ├── src/
│   ├── package.json
│   └── README.md
└── README.md              # Main project documentation
```

## Tech Stack

### Backend
- Spring Boot
- PostgreSQL
- AWS S3 for file storage
- Spring Security
- JWT Authentication
- Elasticsearch (for search functionality)

### Frontend
- React.js
- TypeScript
- Material-UI
- Redux Toolkit
- Axios

## Getting Started

### Prerequisites
- Java 17 or higher
- Node.js 18 or higher
- PostgreSQL
- AWS Account (for S3)
- Maven

### Backend Setup
1. Navigate to the backend directory
2. Run `mvn spring-boot:run`

### Frontend Setup
1. Navigate to the frontend directory
2. Run `npm install`
3. Run `npm start`

## Features
- User authentication and authorization
- File upload and download
- File sharing and collaboration
- File versioning
- Search functionality
- Role-based access control
- File metadata management

## Development
- Backend runs on: http://localhost:8080
- Frontend runs on: http://localhost:3000

## Contributing
Please read CONTRIBUTING.md for details on our code of conduct and the process for submitting pull requests.

## License
This project is licensed under the MIT License - see the LICENSE file for details 
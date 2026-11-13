#LinkForge API Specification v1

## Base URL

/api/v1/

## Authentication

POST /auth/register/
POST /auth/login/

## URL Management

GET /urls/
POST /urls/
GET /urls/{id}/
PATCH /urls/{id}/
DELETE /urls/{id}/

## Analytics

GET /urls/{id}/analytics/

## Redirection

GET /{short_code}

## Technologies

- Django
- Django REST Framework
- MongoDB
- PyMongo

## API Design Principles

- RESTful resource-based endpoints
- HTTP methods for operations
- JSON request and response bodies
- Appropriate HTTP status codes
- API versioning using v1

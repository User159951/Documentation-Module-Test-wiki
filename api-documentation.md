# API Documentation

Complete API documentation with endpoints:

## Endpoints
- `GET /users/{id}` - Added new response fields
- `POST /users` - Updated request body format
- `PUT /users/{id}` - Added validation rules

## Error Response Format
```json
{
  "error": {
    "code": "VALIDATION_ERROR",
    "message": "Invalid input data",
    "details": {
      "field": "email",
      "reason": "Invalid email format"
    }
  }
}
```
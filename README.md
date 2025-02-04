# Number Classification API

This is a FastAPI application that classifies numbers and provides interesting mathematical properties and fun facts about them.

## Endpoints

### GET /api/classify-number

Accepts a number as a query parameter and returns JSON with mathematical properties and a fun fact.

### Request
```http
GET <http://127.0.0.1:8000>/api/classify-number?number=371

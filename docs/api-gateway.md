# API Gateway

## Routes
- /api/v1/* → backend-service:8080
- /auth/* → auth-service:8081

## Rate Limits
- Anonymous: 100 req/min
- Authenticated: 1000 req/min

---
layout: default
title: Authentication and Authorization Guide
---

# API Authentication Example

## Login Request

POST /api/login

### Request Body

```json
{
  "username": "user@example.com",
  "password": "securePassword123"
}
```

### Response

```json
{
  "access_token": "exampletoken123",
  "token_type": "Bearer",
  "expires_in": 3600
}
```

### Accessing Protected Resource

GET /api/profile

Authorization Header
Authorization: Bearer <access_token>
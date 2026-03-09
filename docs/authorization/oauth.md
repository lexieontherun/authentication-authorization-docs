---
layout: default
title: Authentication and Authorization Guide
---

# OAuth 2.0 Authorization

OAuth 2.0 is a widely used authorization framework that allows applications to access resources on behalf of a user.

OAuth issues **access tokens** after successful authentication.

Applications use these tokens to request protected resources.

## Typical OAuth Flow

1. User logs into application
2. Authorization server verifies identity
3. Authorization server issues an access token
4. Client application uses the token to access protected resources
---
layout: default
title: Authentication and Authorization Guide
---

# Authentication Flow

```mermaid
flowchart TD

User --> Login
Login --> Authentication
Authentication --> IdentityVerified
IdentityVerified --> Authorization
Authorization --> AccessGranted
AccessGranted --> Resource
```
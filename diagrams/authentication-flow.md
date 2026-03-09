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
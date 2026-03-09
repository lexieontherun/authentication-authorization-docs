---
layout: default
title: Authentication vs Authorization
---

# Authentication vs Authorization

Authentication and authorization are often confused but serve different purposes.

| Feature | Authentication | Authorization |
|------|------|------|
| Purpose | Verify identity | Grant permissions |
| Occurs | Before authorization | After authentication |
| Methods | Passwords, biometrics, tokens | Roles, attributes, policies |
| Tokens | ID tokens | Access tokens |

## Example Scenario

1. A user logs into a system.
2. Authentication verifies the user's identity.
3. Authorization determines what resources the user can access.
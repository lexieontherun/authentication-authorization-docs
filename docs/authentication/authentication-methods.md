---
layout: default
title: Authentication and Authorization Guide
---

# Authentication Methods

Authentication methods verify user identity using different forms of credentials.

## Single-Factor Authentication (SFA)

Single-factor authentication requires only one credential, typically a password.

Although simple to implement, this method provides limited security because passwords can be stolen or guessed.

## Multifactor Authentication (MFA)

Multifactor authentication requires multiple authentication factors.

Common factor categories include:

### Knowledge

Information known by the user.

Examples:

- passwords
- PIN codes

### Possession

Objects owned by the user.

Examples:

- security keys
- authenticator apps

### Inherence

Biological traits of the user.

Examples:

- fingerprint recognition
- facial recognition

## Single Sign-On (SSO)

Single sign-on allows users to authenticate once and access multiple applications without repeated logins.

Benefits include:

- improved user experience
- reduced password fatigue
- centralized authentication management

## Risk-Based Authentication (RBA)

Risk-based authentication dynamically adjusts authentication requirements depending on risk signals.

Risk signals may include:

- unusual location
- unfamiliar device
- abnormal login behavior

If risk increases, additional authentication steps may be required.

## Passwordless Authentication

Passwordless authentication removes the need for traditional passwords.

Common approaches include:

### Passkeys

Encrypted credentials stored on a user's device and verified using biometrics or a PIN.

### Security Tokens

Hardware-based authentication keys compliant with standards such as FIDO2.

## Continuous Authentication

Continuous authentication monitors user activity throughout an active session.

If suspicious behavior is detected, the system may request re-authentication or terminate the session.

## Decentralized Identity

Decentralized identity gives users control over their credentials.

Instead of relying on centralized identity providers, credentials are stored in digital wallets and verified using blockchain-based technologies.
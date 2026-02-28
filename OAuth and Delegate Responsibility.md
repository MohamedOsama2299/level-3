# OAuth and Delegate Responsibility

## :contentReference[oaicite:0]{index=0}

### What is OAuth?

**OAuth** is an authorization protocol that allows an application to access user data from another application **without sharing the password**.

### Main Idea
- Instead of giving your password to an application.
- You grant **limited and temporary permission** to access specific data.

### Common Use Cases
- Login using Google or Facebook inside another website.
- Accessing user profile data safely.

### Advantages
- Better security because passwords are not shared.
- Control over permissions.
- Temporary access tokens are used.

---

## Delegate Responsibility

### What does Delegate Responsibility mean?

Delegate responsibility means **assigning a task to another service or application instead of handling it directly**.

### Relationship with OAuth

- OAuth is based on the concept of delegation.
- The application delegates authentication or authorization to a trusted service.

### Example

- Website A needs user authentication.
- Instead of storing passwords:
  - It delegates authentication to Google.

---

## Difference Between OAuth and Delegate Responsibility

| Concept | Description |
|---|---|
| OAuth | A technical authorization protocol |
| Delegate Responsibility | A general design concept of distributing tasks |

---

## Summary

- OAuth is used for secure authorization.
- Delegate responsibility improves system design.
- OAuth helps applications avoid storing sensitive credentials.

---
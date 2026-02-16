# Backend Requirement Specifications - ALX Airbnb Project

This document outlines the technical and functional requirements for key backend features of the ALX Airbnb Project.

---

## 1. User Authentication

### Description
Enables users to register, log in, log out, and manage their profiles securely.

### API Endpoints
- **POST /api/auth/register** – Register a new user  
- **POST /api/auth/login** – Log in existing user  
- **POST /api/auth/logout** – Log out current user  
- **GET /api/users/:id** – Fetch user profile  
- **PUT /api/users/:id** – Update user profile  

### Input / Output Specifications
**Register Input:**  
```json
{
  "name": "John Doe",
  "email": "john@example.com",
  "password": "Password123!"
}

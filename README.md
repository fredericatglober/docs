# Glober API Docs

Welcome to the Glober Platform API documentation.

We offer two main sets of endpoints:
- 🟢 **Project API** (create, update, and manage translation projects)
- 🔐 **Auth API** (register, login, token management)

👇 Scroll down or use the left menu to explore the endpoints.

---

## Getting Started

You can start using the API by making a health check call:

GET https://dev-project.api.glober.ai/health


---

## Auth Overview

1. **Register:**  
   `POST /api/v1/auth/register`

2. **Login:**  
   `POST /api/v1/auth/login`

You’ll receive a token to authenticate other requests.

---

## Project API Flow

1. Create a Project  
2. Upload Assets  
3. Get Results  
4. Rerun if needed

---

_For more, use the API Explorer to the left._

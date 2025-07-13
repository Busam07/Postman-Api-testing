# API Testing Project – Reqres API (Postman + Newman )

This project automates the testing of public APIs from [Reqres.in](https://reqres.in/) using Postman and Newman. It validates key API endpoints (GET, POST, PUT, DELETE).

---

## 🔧 Tools & Technologies
- **Postman** – API request and test automation
- **Newman** – CLI tool to run Postman collections
- **JSON** – For request payload and schema
- **GitHub** – Version control

---

## ✅ Test Coverage
- `GET /users?page=2` – List users
- `GET /users/{id}` – Single user details
- `POST /users` – Create a user
- `PUT /users/{id}` – Update user data
- `DELETE /users/{id}` – Delete a user

Includes:
- Status code validation
- Response body structure validation
- Schema checks
- Edge-case scenarios

---

## 🚀 How to Run Tests

### 🔹 Run via Postman GUI
1. Import the `Reqres.postman_collection.json` into Postman.
2. Click "Run" using the Collection Runner.
3. Review test results and response validations.

### 🔹 Run via Newman CLI
Make sure you have Node.js + Newman installed:
```bash
npm install -g newman

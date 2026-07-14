# QA API Testing with Postman

## 📌 Project Overview

This project demonstrates API testing skills using **Postman** and the **ReqRes** REST API. It includes GET and POST requests, request validation, authentication headers, response verification, and automated test scripts.

The objective of this project is to showcase API testing fundamentals following QA best practices.

---

## 🛠️ Technologies Used

- Postman
- REST API
- JSON
- HTTP Methods (GET, POST)
- JavaScript (Postman Tests)
- ReqRes API

---

## 📂 Project Structure

```
QA_API_Testing_Postman_Project
│
├── Get data
├── Post data
├── Environment (QA)
└── Documentation
```

---

## 🚀 API Tested

ReqRes API

https://reqres.in/

---

## 📋 Test Scenarios

### ✅ GET Users

**Endpoint**

```
GET /api/users?page=2
```

**Validations**

- Status Code is 200
- Response time validation
- Response contains data
- Users list is returned successfully

---

### ✅ POST Create User

**Endpoint**

```
POST /api/users
```

**Request Body**

```json
{
  "name": "Ana",
  "job": "QA Analyst"
}
```

**Validations**

- Status Code is 201
- User created successfully
- Response contains id
- Response contains createdAt

---

## 🔑 Authentication

The project uses the ReqRes API Key.

Header:

```
x-api-key: YOUR_API_KEY
```

---

## ✅ Automated Tests

Examples of Postman Tests:

- Verify Status Code
- Verify Response Time
- Verify Response Body
- Verify JSON Properties
- Verify Created User

---

## 📷 Sample Response

GET Request

```json
{
  "page": 2,
  "data": [
    {
      "id": 7,
      "email": "michael.lawson@reqres.in"
    }
  ]
}
```

## Screenshots

### GET Request

![GET Request](images/get-request.png)

### POST Request

![POST Request](images/post-request.png)

### Collection

![Collection](images/postman-collection.png)

### Tests Passed

![Tests](images/tests-passed.png)

---

## 🎯 Learning Objectives

- Understand REST APIs
- Execute HTTP requests
- Validate API responses
- Use Headers and Parameters
- Work with API Keys
- Create automated Postman tests

---

## 👩‍💻 Author

**Ana Centeno**

QA Analyst | Software Tester

LinkedIn:
https://www.linkedin.com/in/ana-centeno-tech/

GitHub:
https://github.com/AnaCenteno-DA

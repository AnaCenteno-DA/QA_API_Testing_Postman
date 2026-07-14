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

<img width="1280" height="733" alt="Captura Postman2_" src="https://github.com/user-attachments/assets/0e78a109-4609-49fa-8f3b-02d0b8ee56cf" />

### POST Request

<img width="1282" height="733" alt="Captura Postman2_5_" src="https://github.com/user-attachments/assets/801bf03a-d677-44f2-a512-aa2fb43d3cc6" />

### PUT Request

<img width="1286" height="729" alt="Captura Postman3_3" src="https://github.com/user-attachments/assets/1dac9b3f-e3e9-4926-8579-c757577724ce" />

### DELETE Request

<img width="1286" height="730" alt="Captura Postman4" src="https://github.com/user-attachments/assets/0d3cb5e8-b14e-466e-8672-be73b22bde03" />


### Collection



### Tests Passed




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

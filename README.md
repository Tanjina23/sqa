# 🧪 QA Testing – Manual & API Testing

This repository contains professional QA documentation samples for **manual testing** and **API testing** using demo websites. These documents can be used to demonstrate your testing process, attention to detail, and ability to work with different web applications and APIs.

---

## 📘 Included Files

- `[Bug Report.pdf](https://github.com/user-attachments/files/20174408/Bug.Report.pdf)
`  
  Sample bug reports with details like bug ID, module, severity, reproduction steps.

- `[Test Case.pdf](https://github.com/user-attachments/files/20174416/Test.Case.pdf)
`  
  Sample test cases for both UI and API testing, including test data, expected vs actual results, and pass/fail status.

---

## 🔍 Projects Used for Testing

### 1. 🌐 [AutomationExercise.com](https://automationexercise.com)
- **Type**: Web UI & API Testing
- **Use Cases**:
  - Signup form validation (manual testing)
  - REST API (e.g., GET all products, POST login)
- **Bug Example**:
  - Signup form accepts invalid email formats

### 2. 🔗 [Reqres.in](https://reqres.in)
- **Type**: API Testing (Mock API)
- **Use Cases**:
  - Test login, registration, user list, error handling
  - Status code validation and error message handling
- **Bug Example**:
  - Login API returns 500 error for empty request body

### 3. 🛍️ [OpenCart Demo](https://demo.opencart.com)
- **Type**: Manual Functional Testing
- **Use Cases**:
  - Product search functionality
  - Cart management
  - Checkout and registration
- **Test Case Example**:
  - Verifying product search returns relevant results

---

## 🧰 Tools & Skills Used

| Area             | Tools / Skills             |
|------------------|----------------------------|
| Manual Testing   | Browser DevTools, Word     |
| API Testing      | Postman, Swagger UI        |
| Documentation    | MS Word                    |
| Test Design      | Functional Test Cases, Bug Reporting |
| Collaboration    | GitHub Repository          |

---


## ✅ Sample Bug Report

| Field          | Value                                                        |
|----------------|--------------------------------------------------------------|
| Bug ID         | BUG_002                                                      |
| Title          | Login API returns 500 on empty body                          |
| Module         | Reqres API (/api/login)                                      |
| Severity       | High                                                         |
| Steps          | Send empty POST request                                      |
| Expected       | 400 Bad Request with proper error message                    |
| Actual         | 500 Internal Server Error                                     |

---

## ✅ Sample Test Case

| Field          | Value                                                        |
|----------------|--------------------------------------------------------------|
| Test Case ID   | TC_API_001                                                   |
| Title          | Verify login API with valid credentials                      |
| Scenario       | User logs in successfully                                    |
| Steps          | POST /api/login with valid email and password                |
| Expected       | Return 200 OK with token                                     |
| Status         | ✅ Pass                                                      |

---


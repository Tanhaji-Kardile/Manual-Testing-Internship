ReqRes_API_Testing_Postman_Project:

## Project Overview:

This project focuses on API testing of the ReqRes REST API using Postman. The objective is to validate REST API endpoints for functionality, authentication, data retrieval, and response verification.

---

## Project Objective

* Validate REST API endpoints
* Verify request and response structure
* Test authentication and authorization flows
* Validate HTTP status codes
* Perform data validation for API responses
* Execute API collections using Postman and Newman

---

## Tools and Technologies

* Postman
* Newman
* ReqRes API
* REST API
* JSON
* GitHub

---

## Project Structure

```text
01_Project_Introduction
02_Project_Objective
03_Scope_of_Testing
04_Tools_and_Technologies_Used
05_Test_Environment_Setup
06_API_Endpoints_Tested
07_Test_Scenarios_and_Test_Cases
08_Postman_Collection_Structure
09_Request_and_Response_Validation
10_Environment_Variables
11_Run_Execution
12_Test_Results_and_Observations
13_Screenshots
14_Challenges_Faced_and_Resolution
15_Conclusion
16_Deliverables
17_Test_Closure_Report
```

---
## API Endpoints Covered

### 1. Authentication

#### POST - Login

* Verify successful login with valid credentials
* Verify login with invalid credentials
* Verify response status code
* Verify token generation

---

### 2. Users

#### GET - Get the Users

* Retrieve list of users
* Validate response body
* Validate response status code

#### GET - Single User

* Retrieve a specific user by ID
* Validate user details
* Validate response status code

---

### 3. Create User

#### POST - Create User

* Create a new user
* Validate request payload
* Validate response data
* Validate response status code

---

### 4. Update User

#### PUT - Update User

* Update complete user information
* Validate updated response
* Validate response status code

#### PATCH - Update User

* Update partial user information
* Validate updated response
* Validate response status code

---

### 5. Delete User

#### DELETE - Delete User

* Delete user by ID
* Validate response status code
* Validate successful deletion


---

## Validation Approach

* Status code validation
* Response body validation
* Response time validation
* JSON structure validation

---

## Execution Methods

### Postman Collection Runner

* Executed full API collection
* Verified all test cases
* Captured execution results

### Newman Command Execution

```bash
newman run ReqRes_API_Testing.postman_collection.json -e ReqRes_Environment.postman_environment.json
```

---

## Deliverables

* Postman Collection JSON file
* Environment JSON file
* Newman execution report
* Test scenarios & test cases
* Screenshots
* Test closure report

---

## Conclusion

The ReqRes API testing successfully validated all major API operations including authentication, CRUD operations, and response verification using Postman and Newman.

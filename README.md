# Swagger Petstore API Test Cases

## Project Overview

This project focuses on API testing using the Swagger Petstore REST API. It contains a structured Excel spreadsheet documenting test cases for Pet, Store, and User API modules.

The spreadsheet provides test case IDs, HTTP methods, endpoints, request details, expected status codes, expected responses, actual results, and test execution status.

## Project Objectives

- Understand REST API testing fundamentals.
- Test API endpoints using HTTP methods.
- Validate expected status codes and response data.
- Cover positive and negative test scenarios.
- Document test cases in a professional Excel spreadsheet.
- Track actual results and identify failed test cases.

## API Information

- **Project:** Swagger Petstore API Testing
- **API Base URL:** https://petstore.swagger.io/v2
- **Swagger Documentation:** https://petstore.swagger.io/
- **Testing Type:** Manual API Testing
- **Test Documentation:** Microsoft Excel

## API Modules Covered

### 1. Pet API

Example endpoints:

- `POST /pet` — Add a new pet.
- `GET /pet/{petId}` — Find a pet by ID.
- `PUT /pet` — Update an existing pet.
- `DELETE /pet/{petId}` — Delete a pet.
- `GET /pet/findByStatus` — Find pets by status.

### 2. Store API

Example endpoints:

- `GET /store/inventory` — Retrieve store inventory.
- `POST /store/order` — Place an order.
- `GET /store/order/{orderId}` — Find an order by ID.
- `DELETE /store/order/{orderId}` — Delete an order.

### 3. User API

Example endpoints:

- `POST /user` — Create a user.
- `GET /user/{username}` — Retrieve a user by username.
- `PUT /user/{username}` — Update a user.
- `DELETE /user/{username}` — Delete a user.
- `POST /user/login` — Log in a user.
- `POST /user/logout` — Log out a user.

## Test Case Spreadsheet

The Excel workbook contains two worksheets:

1. **API Test Cases** — Structured test cases covering Pet, Store, and User endpoints.
2. **Project Info** — Project overview, API reference, and instructions.

### Test Case Columns

- Test Case ID
- API Name
- HTTP Method
- Endpoint
- Description
- Request Headers
- Request Body
- Expected Status Code
- Expected Response
- Actual Status Code
- Actual Response
- Test Result (Pass/Fail)

## Types of Testing Covered

- Positive testing
- Negative testing
- Functional testing
- CRUD operation testing
- Input validation
- Response status code validation
- Error handling
- API response verification

## Tools and Technologies

- Swagger UI
- Swagger Petstore REST API
- Microsoft Excel
- HTTP methods: GET, POST, PUT, DELETE

## How to Execute the Test Cases

1. Open the Swagger Petstore documentation.
2. Select an endpoint to test.
3. Review the test case and prepare the required request data.
4. Execute the request using Swagger UI or another API testing tool.
5. Record the actual HTTP status code and response.
6. Compare the actual result with the expected result.
7. Mark the test case as Pass or Fail based on the comparison.

**Note:** Expected results are documented test expectations, not confirmed execution results. Verify them against the live API before marking any test case as passed or failed. Some negative scenarios may behave differently depending on the API implementation.

## Project Deliverables

- Excel spreadsheet containing API test cases.
- Documented endpoints and request details.
- Expected and actual response tracking.
- Test execution status tracking.

## Reference Links

- Swagger Petstore: https://petstore.swagger.io/
- Swagger Petstore API Base URL: https://petstore.swagger.io/v2

## Author

**Reshmitha Kukati**

GitHub: https://github.com/kukatireshmitha986-create

---

This project demonstrates practical knowledge of REST API testing, test case design, response validation, and software testing documentation.

# api-testing-jsonplaceholder
This project contains functional testing performed on a public REST API:

https://jsonplaceholder.typicode.com/posts

The goal was to validate expected and unexpected behaviors, analyze HTTP responses, and identify potential issues in data validation.

# Testing Scope

- GET requests
- POST requests
- Positive and negative scenarios
- Response validation
- Error handling


# Tools Used

- Postman
- REST API
- HTTP Protocol


# Key Findings

| ID           | Issue                                            | Severity | Priority |
-----------------------------------------------------------------------------------------
| API-POST-002 | Endpoint accepts invalid data without validation |   HIGH   |   HIGH   |


# Learnings

During testing, I identified that some endpoints do not enforce input validation, which may lead to data integrity issues.
This highlights the importance of backend validation even in simple APIs.


# Project Structure

- '/test-cases' → detailed test cases
- '/bug-reports' → documented bugs
- '/postman_collection' → API requests
- '/evidence' → screenshots

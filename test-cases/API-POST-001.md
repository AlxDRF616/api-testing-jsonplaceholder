# API-POST-001 – Successful POST request

## Description
Verify API behavior when sending valid data in a POST request.


## Endpoint
POST /posts


## Test Data
{
  "title": "test",
  "body": "probando",
  "userId": 1
}


## Steps

1. Send POST request with valid payload
2. Observe response


## Expected Result
API should accept the request with a confirmation status (e.g., 201 Created)


## Actual Result
Request is accepted and returns status 201 Created


## Status
Successful
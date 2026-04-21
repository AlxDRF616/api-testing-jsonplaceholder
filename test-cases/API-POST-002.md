# API-POST-002 – Invalid POST accepted

## Description
Verify API behavior when sending incomplete or invalid data in a POST request.


## Endpoint
POST /posts


## Test Data
{
  "title": "",
  "body": "",
  "userId": null
}


## Steps

1. Send POST request with invalid payload
2. Observe response


## Expected Result
API should reject the request with a validation error (e.g., 400 Bad Request)


## Actual Result
Request is accepted and returns status 201 Created


## Status
Failed

# API-GET-002 – Invalid GET request

## Description
Verify API behavior when requesting invalid information in a GET request.


## Endpoint
GET /posts/101


## Received Data
{}


## Steps

1. Send GET request with "101" as ID (/posts/101)
2. Observe response


## Expected Result
API should get a negative response (e.g., 404 Not Found)


## Actual Result
Invalid request, the post does not exist and returns status 404 Not Found


## Status
Successful
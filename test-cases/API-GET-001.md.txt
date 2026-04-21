# API-GET-001 – Successful GET request

## Description
Verify API behavior when requesting information in a GET request.


## Endpoint
GET /posts/1


## Acquired Data
{
    "userId": 1,
    "id": 1,
    "title": "sunt aut facere repellat provident occaecati excepturi optio reprehenderit",
    "body": "quia et suscipit\nsuscipit recusandae consequuntur expedita et cum\nreprehenderit molestiae ut ut quas 		totam\nnostrum rerum est autem sunt rem eveniet architecto"
}


## Steps

1. Send GET request with "1" as ID (/posts/1)
2. Observe response


## Expected Result
API should have a successful GET response (e.g., 200 OK Request)


## Actual Result
Request is accepted and returns status 200 OK


## Status
Successful
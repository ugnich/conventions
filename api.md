## OpenAPI

Use OpenAPI v3, YAML format. Try to avoid duplicating, use $ref generously.

## Authentication

Bearer Token in `Authorization` HTTP request headers. See [RFC 6750](https://tools.ietf.org/html/rfc6750)

Request a token using `/auth/signup` or `/auth/login` endpoints, providing `email` and `password` as query parameters.  
Reset a password using `/auth/reset`.

## HTTP methods

`GET` for retrieving  
`POST` for creating new objects and performing non-idempotent actions on existing objects  
`DELETE` for deleting  
`PUT` for replacing an existing object  
`PATCH` for changing attributes of existing objects

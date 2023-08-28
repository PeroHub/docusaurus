---
sidebar_position: 7
---

# Update - user - profile

#### Method - put

This endpoint allows for users to update their profile details. To use this endpoint you need to make a put request to the `/users/profile/update` endpoint with a request body as shown below:

```
{
  "email": "string",
  "first_name": "string",
  "last_name": "string",
  "country_code": "string",
  "phone_number": "string",
  "country": "string",
  "state": "string"
}

```

A status code of `200` - **success** - shows that the request is successful.
Status code of `422` - **validation error** - shows something is wrong in your request body

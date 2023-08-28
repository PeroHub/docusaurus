---
sidebar_position: 11
---

# Update - user

#### Method - put

This endpoint allows you to update details about the currently logged in user.

Send a **put** request to `/users/{user_id}` and ensure that `{user_id}` is provided a parameter as it is required.

Your request body will look like this:

```
{
  "email": "string",
  "id": "string",
  "first_name": "string",
  "last_name": "string",
  "phone_number": "string",
  "password": "string"
}

```

A status of `200` means the request is successful while `422` means the request body keys are missing or provided in the wrong format.

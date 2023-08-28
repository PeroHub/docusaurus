---
sidebar_position: 12
---

# Activate - user

#### Method - put

This endpoint allows a super user to activate a user, to use this endpoint user must be a super user. You need to make a **put** request to the `/users/{user_id}/activate` endpoint with a specified body of request to activate a user

Your request body should look like this:

```
{
  "email": "string",
  "is_active": true
}

```

You'll get a `200` response status code if the request to the endpoint is successful.

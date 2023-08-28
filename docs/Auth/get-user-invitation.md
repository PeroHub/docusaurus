---
sidebar_position: 10
---

# Get - user - invitations

#### Method - get

This endpoint will provide you with detail status of your users invitation to your project.

So make a **get** request to `/users/{user_id}/invites` for this information

**Please note**

- `{user_id}` is needed as part of the parameter on the endpoint to have a success response

Your success response will look like this

```
[
  {
    "organization_id": "string",
    "user_id": "string",
    "email": "string",
    "role_id": "string",
    "invite_code": "string",
    "is_accepted": "string",
    "is_revoked": "string",
    "organization": {
      "id": "string",
      "name": "string",
      "user_id": "string"
    },
    "role": {
      "role_name": "string",
      "organization_id": "string",
      "permissions": [
        "string"
      ]
    }
  }
]

```

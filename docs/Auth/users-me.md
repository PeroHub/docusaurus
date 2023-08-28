---
sidebar_position: 9
---

# Users - me

#### Method - get

You can now use this endpoint to retrieve details about a currently logged in user.

To achieve this, make a **get** request to `/users/me` and you can provide refresh token optionally to the url.

Your `200` success response will look like this sample below:

```
{
  "email": "string",
  "id": "string",
  "first_name": "string",
  "last_name": "string",
  "phone_number": "string",
  "is_active": true,
  "has_password": true,
  "is_verified": true,
  "is_superuser": true,
  "org_user": [
    {
      "id": "string",
      "organization_id": "string",
      "user_id": "string",
      "role_id": "string",
      "user_permissions": [
        "string"
      ],
      "is_deleted": true,
      "date_created": "2023-08-26T10:26:03.792Z",
      "last_updated": "2023-08-26T10:26:03.792Z",
      "role": {
        "role_name": "string",
        "organization_id": "string",
        "permissions": [
          "string"
        ]
      }
    }
  ],
  "country_code": "string",
  "image_url": "string",
  "is_deleted": true,
  "device_id": "string",
  "country": "string",
  "state": "string",
  "google_id": "string",
  "google_image_url": "string",
  "date_created": "2023-08-26T10:26:03.793Z",
  "last_updated": "2023-08-26T10:26:03.793Z"
}

```

---
sidebar_position: 1
---

# Sign up - create user

The sign up endpoint allows you to create a new user for you product.

Please **note** the **base url** is `https://staging.app-api.timbu.com`

To create a new user, you will need to send a **post** request to the `/auth/signup` endpoint with a body of request containing details of the new user.

#### Here is a example of how your request body should look

```
{
  "email": "string",
  "password": "string",
  "first_name": "string",
  "last_name": "string",
  "phone_number": "string",
  "phone_country_code": "string",
  "image_url": "string",
  "device_id": "string",
  "google_id": "string",
  "google_image_url": "string"
}

```

If everything goes well, you will get a `201` success satus code. And if parameter added are not in the right format, you will get a `422` validation Error

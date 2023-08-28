---
sidebar_position: 3
---

# Admin - signup

To register and admin for your project, please make a call to this endpoint `auth/admin-signup` with the example parameter values below:

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

If everything goes well, you will get a `200` success satus code. And if parameter added are not in the right format or missing, you will get a `422` validation Error

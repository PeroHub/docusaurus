---
sidebar_position: 5
---

# Customer - login

#### Method - post

Use this endpoint to login your customer by sending a **post** request to `/auth/customer-login` endpoint.

Your request body should look like this -

```
{
  "email": "string",
  "password": "string",
  "organization_id": "string",
  "app_url": "string"
}

```

If everything goes well, you will get a `200` success satus code. If the request values in the body are not in the right format or missing, you will get a `422` validation Error

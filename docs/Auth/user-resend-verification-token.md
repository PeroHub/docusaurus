---
sidebar_position: 14
---

# Users - resend - verification - token

#### Method - post

This endpoint can be used to trigger a resend of a user's verification token by making a request to `/users/resend-verification/token`

Example request body:

```
{
  "email": "string",
  "redirect_url": "string"
}

```

A status code of `200` - **success** - shows that the request is successful.
Status code of `422` - **validation error** - shows something is wrong in your request body

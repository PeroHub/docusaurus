---
sidebar_position: 8
---

# User-recover-password

#### Method - post

This endpoint allows for password recovery. All you need to do is call the endpoint `/users/recover-password` and pass the users email in your request body.

Here is an example:

```
{
  "email": "string"
}

```

A status code of `200` - **success** - shows that the request is successful.
Status code of `422` - **validation error** - shows something is wrong in your request body

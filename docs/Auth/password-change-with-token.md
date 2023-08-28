---
sidebar_position: 15
---

# Password - change - with - token

#### Method - put

You can easily change users password by sending a **put** request to `/users/password-change/token/{token}`

**Please note** `{token}` parameter is required in the url

Here is a example request body you should follow:

```
{
  "code": "string",
  "password": "string"
}

```

A status code of `200` - **success** - shows that the request is successful.
Status code of `422` - **validation error** - shows something is wrong in your request body

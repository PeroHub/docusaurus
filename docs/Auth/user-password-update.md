---
sidebar_position: 13
---

# User - password - update

#### Method - patch

You can now use this endpoint to update your users password. To do that, please make a **patch** request to `/users/password/update`

Set up your request body to use this format:

```
{
  "password": "string",
  "password_confirmation": "string"
}
```

A status code of `200` - **success** - shows that the request is successful.
Status code of `422` - **validation error** - shows something is wrong in your request body

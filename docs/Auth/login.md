---
sidebar_position: 2
---

# Login

#### Method - post

The login endpoint allows you to login an existing user into the product you are building after they must have signed up

And to login a user, you need to make a **post** request to the `/auth/login` endpoint with a required body of requst as specified below:

```
{
  "email": "string",
  "phone_number": "string",
  "phone_country_code": "string",
  "device_id": "string",
  "password": "string"
}
```

**email** -> This is the email of the existing user
**phone_number** This is the phone number of the existing user
**country_code** This is the country code of the existing user
**password** This is the password of the existing user.

If everything goes well, you will get a `200` success satus code. And if parameter added are not in the right format or missing, you will get a `422` validation Error

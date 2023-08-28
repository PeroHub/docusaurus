---
sidebar_position: 4
---

# Logout

To log out an authenticated user, make a **post** request to this endpoint `auth/logout` and provide the refresh token. **please note the refresh token is optional**

You will get a `200` satus code on success. And if the parameters added are not in the right format or missing, you will get a `422` validation Error

---
sidebar_position: 8
---

# Refresh-access-token

#### Method - get

With the refresh token set in the client during the auth flow, you can now use this token to request a new access token.

To do this, please send a **get** request to `/auth/refresh-access-token` by passing in the refresh token as a parameter to the endpoint.

You will get a `200` satus code on success. And if you added the wrong parameter in the url, you will get a `422` validation Error.

---
sidebar_position: 16
---

# Upload - user - image

#### Method - patch

You can use this endpoint to update a user's image

To use this endpoint you need to make a **patch** request to the `/users/image/upload` endpoint with the image file as payload and the user authorization/bearer token

Remember the users image should come as a form data in the request body

A status code of `200` - **success** - shows that the request is successful.
Status code of `422` - **validation error** - shows something is wrong in your request body

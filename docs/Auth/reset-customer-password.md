---
sidebar_position: 6
---

# Reset-customer-password

#### Method - post

Use this endpoint to give your users the ability to reset their password if they have issues accessing their account.

Make a call to `/users/reset-password` and set your request body as shown below:

```
{
  "email": "string",
  "code": "string",
  "password": "string"
}

```

- **email** -> This is the email address of the user
- **code** -> This is a unique code sent to the user on password recovery
- **password** -> This is the registered password of the user

If everything goes well, you will get a `200` success satus code. If the request values in the body are not in the right format or missing, you will get a `422` validation Error

<!-- - Read the [official documentation](https://docusaurus.io/)
- Modify your site configuration with [`docusaurus.config.js`](https://docusaurus.io/docs/api/docusaurus-config)
- Add navbar and footer items with [`themeConfig`](https://docusaurus.io/docs/api/themes/configuration)
- Add a custom [Design and Layout](https://docusaurus.io/docs/styling-layout)
- Add a [search bar](https://docusaurus.io/docs/search)
- Find inspirations in the [Docusaurus showcase](https://docusaurus.io/showcase)
- Get involved in the [Docusaurus Community](https://docusaurus.io/community/support) -->

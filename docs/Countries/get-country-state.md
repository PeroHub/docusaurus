---
sidebar_position: 2
---

# Get - countries - state

#### Method - get

This endpoint returns a list of states for a particular queried country. To get this data you need to make a get request to the `/countries/{country_code}/states` endpoint.

You must pass in the code of the country you want to query as a parameter in the url to get the desire output.

The success message will come in this format:

```
{
  "name": "string",
  "state_code": "string"
}

```

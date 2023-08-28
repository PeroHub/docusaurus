---
sidebar_position: 3
---

# Get - countries - dial - code

#### Method -get

You can use this endpoint to fetch a list of all countries and their respective codes including dial codes.

To use this endpoint, you need to make a **get** request to `/countries/codes `endpoint

To query for a particular country, you need to make a get request to /countries/codes endpoint and and append `?country_code={country_code}` to the end of the url. Your url will look like this `/countries/codes?country_code={country_code}`

The success response is going to look like this

```
{
  "name": "string",
  "iso3": "string",
  "iso2": "string",
  "dial_code": "string",
  "states": [
    {
      "name": "string",
      "state_code": "string"
    }
  ]
}

```

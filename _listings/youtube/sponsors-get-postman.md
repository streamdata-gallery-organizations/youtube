{
  "info": {
    "name": "Youtube Get Sponsors",
    "_postman_id": "42106b56-0778-46a6-ad14-64d1d5f26d89",
    "description": "Lists sponsors for a channel.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "sponsors",
      "item": [
        {
          "id": "df5c7a1f-0441-42dd-aec7-db3dd1476ae5",
          "name": "getSponsors",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/sponsors?filter=%7B%7D&maxResults=%7B%7D&pageToken=%7B%7D&part=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists sponsors for a channel"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2c6e42ce-2d9d-4e1f-9567-2c8de7d9e234"
            }
          ]
        }
      ]
    }
  ]
}
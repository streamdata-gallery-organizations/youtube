{
  "info": {
    "name": "Youtube Get Fanfundingevents",
    "_postman_id": "e28a3871-765b-4ba0-ab25-120a3946516e",
    "description": "Lists fan funding events for a channel.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "fanfundingevents",
      "item": [
        {
          "id": "f8b70d77-49aa-475c-929f-553947c8d81c",
          "name": "getFanfundingevents",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/fanFundingEvents?hl=%7B%7D&maxResults=%7B%7D&pageToken=%7B%7D&part=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists fan funding events for a channel"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c013e31a-c33c-4419-8a7f-8880bd14e05a"
            }
          ]
        }
      ]
    }
  ]
}
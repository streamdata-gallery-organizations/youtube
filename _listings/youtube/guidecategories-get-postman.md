{
  "info": {
    "name": "Youtube Get Guecategories",
    "_postman_id": "207c8791-c2db-4da0-bb9c-065869fefa68",
    "description": "Returns a list of categories that can be associated with YouTube channels.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "guecategories",
      "item": [
        {
          "id": "ab28a190-73f8-4722-bb5e-7dd11e443d0d",
          "name": "getGuecategories",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/guideCategories?hl=%7B%7D&id=%7B%7D&part=%7B%7D&regionCode=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of categories that can be associated with YouTube channels"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ff2e75e1-8895-4f9d-9779-9cedbdc32b69"
            }
          ]
        }
      ]
    }
  ]
}
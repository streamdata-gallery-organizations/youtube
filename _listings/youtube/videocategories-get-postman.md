{
  "info": {
    "name": "Youtube Get Veocategories",
    "_postman_id": "fb691d44-0e13-48c7-97a9-ad462197e708",
    "description": "Returns a list of categories that can be associated with YouTube videos.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "veocategories",
      "item": [
        {
          "id": "39980e84-dcea-4f50-a0de-cb9d6617db83",
          "name": "getVeocategories",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/videoCategories?hl=%7B%7D&id=%7B%7D&part=%7B%7D&regionCode=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of categories that can be associated with YouTube videos"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7726a50e-c56c-4045-b670-7c25e57e5659"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Youtube Delete Comments",
    "_postman_id": "62ff3632-401c-417f-9bfd-db56f434e86d",
    "description": "Deletes a comment.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "comments",
      "item": [
        {
          "id": "9c97e73d-4864-424d-9a35-82fd731e3c7e",
          "name": "deleteComments",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/comments?id=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a comment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b99ba972-1714-4274-beea-712ce419acd3"
            }
          ]
        }
      ]
    }
  ]
}
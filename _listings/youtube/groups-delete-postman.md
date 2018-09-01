{
  "info": {
    "name": "Youtube Delete Groups",
    "_postman_id": "2edd7ec1-61ce-4f1d-9110-1741cd66af9b",
    "description": "Deletes a group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "groups",
      "item": [
        {
          "id": "8c50bb24-6202-4fcd-85ae-cdf4b83683d6",
          "name": "deleteGroups",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/groups?id=%7B%7D&onBehalfOfContentOwner=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b5250464-adbe-4b09-bcf5-fd5386a564d4"
            }
          ]
        }
      ]
    }
  ]
}
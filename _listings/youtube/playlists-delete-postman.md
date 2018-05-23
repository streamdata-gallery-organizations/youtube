{
  "info": {
    "name": "Youtube Delete Playlists",
    "_postman_id": "c6b94710-977c-4cf4-a7f3-89d570b6deba",
    "description": "Deletes a playlist.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "playlists",
      "item": [
        {
          "id": "f5e47ff3-e514-4875-9508-b4ee2de16429",
          "name": "deletePlaylists",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/playlists?id=%7B%7D&onBehalfOfContentOwner=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a playlist"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ed646eb-d18b-4ad4-8c2c-cd749f0aa06c"
            }
          ]
        }
      ]
    }
  ]
}
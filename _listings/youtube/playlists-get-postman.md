{
  "info": {
    "name": "Youtube Get Playlists",
    "_postman_id": "90b0d5ea-79f1-4868-9fcb-c16059e9c2d8",
    "description": "Returns a collection of playlists that match the API request parameters. For example, you can retrieve all playlists that the authenticated user owns, or you can retrieve one or more playlists by their unique IDs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "playlists",
      "item": [
        {
          "id": "03d63f4a-173a-4a4f-83a9-ee395ceaeb97",
          "name": "getPlaylists",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/playlists?channelId=%7B%7D&hl=%7B%7D&id=%7B%7D&maxResults=%7B%7D&mine=%7B%7D&onBehalfOfContentOwner=%7B%7D&onBehalfOfContentOwnerChannel=%7B%7D&pageToken=%7B%7D&part=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a collection of playlists that match the API request parameters"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5741eba3-c3dc-441c-a667-878066f94821"
            }
          ]
        }
      ]
    }
  ]
}
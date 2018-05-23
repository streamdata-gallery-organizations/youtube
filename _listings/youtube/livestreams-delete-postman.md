{
  "info": {
    "name": "Youtube Delete Livestreams",
    "_postman_id": "46102b1b-6c75-4030-b6f3-ffd2fcccca5a",
    "description": "Deletes a video stream.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "livestreams",
      "item": [
        {
          "id": "8631604b-0286-4699-9e43-073371eb7202",
          "name": "deleteLivestreams",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/liveStreams?id=%7B%7D&onBehalfOfContentOwner=%7B%7D&onBehalfOfContentOwnerChannel=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a video stream"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6d4e9347-9686-466b-b213-9412056baa59"
            }
          ]
        }
      ]
    }
  ]
}
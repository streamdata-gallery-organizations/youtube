{
  "info": {
    "name": "Youtube Add Watermarks Unset",
    "_postman_id": "f460d1ff-143e-4c78-a688-dfa4a6d3407a",
    "description": "Deletes a channel's watermark image.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "watermarks",
      "item": [
        {
          "id": "3dd230ab-f442-422f-a1b6-e15385383a8e",
          "name": "postWatermarksUnset",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/watermarks/unset?channelId=%7B%7D&onBehalfOfContentOwner=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a channel's watermark image"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1c4f402e-56c7-44c9-acfe-7d638dd24b69"
            }
          ]
        }
      ]
    }
  ]
}
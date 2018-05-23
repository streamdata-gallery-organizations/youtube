{
  "info": {
    "name": "Youtube Get Channel Sections",
    "_postman_id": "29ed432c-1e0a-4b90-8f92-ded37e199c2e",
    "description": "Returns channelSection resources that match the API request criteria.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "channelsections",
      "item": [
        {
          "id": "caf9df83-e76f-44c7-ab79-e29298411c39",
          "name": "getChannelsections",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/channelSections?channelId=%7B%7D&hl=%7B%7D&id=%7B%7D&mine=%7B%7D&onBehalfOfContentOwner=%7B%7D&part=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns channelSection resources that match the API request criteria"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c2a48e0f-9dce-4b42-958d-e92d84a6ded4"
            }
          ]
        }
      ]
    }
  ]
}
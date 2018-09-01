{
  "info": {
    "name": "Youtube Delete Channel Sections",
    "_postman_id": "016fb3e5-8d84-42ec-a182-739df0a86067",
    "description": "Deletes a channelSection.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "channelsections",
      "item": [
        {
          "id": "94f31523-f379-4568-8910-4b44c2ee8c22",
          "name": "deleteChannelsections",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/channelSections?id=%7B%7D&onBehalfOfContentOwner=%7B%7D",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a channelSection"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "72e9e289-cb9e-4c53-aeba-fea0a25d2f71"
            }
          ]
        }
      ]
    }
  ]
}
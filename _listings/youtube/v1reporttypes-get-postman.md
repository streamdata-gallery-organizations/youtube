{
  "info": {
    "name": "Youtube Get Reporttypes",
    "_postman_id": "cb45d152-5158-43be-ab7c-b24b8e80e9d7",
    "description": "Lists report types.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "v1",
      "item": [
        {
          "id": "06ecfa9f-9d89-4536-bdcc-4ec9f2a81d0c",
          "name": "getV1Reporttypes",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/v1/reportTypes?includeSystemManaged=%7B%7D&onBehalfOfContentOwner=%7B%7D&pageSize=%7B%7D&pageToken=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists report types"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8f103048-0452-4e7e-81c4-5413770f94e6"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Youtube Add Comments Set Moderation Status",
    "_postman_id": "a7ed6ce0-61c6-4666-9f1f-aff9cbed2cd1",
    "description": "Sets the moderation status of one or more comments. The API request must be authorized by the owner of the channel or video associated with the comments.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "comments",
      "item": [
        {
          "id": "6271397c-a215-42f1-9008-61315c4e6480",
          "name": "postCommentsSetmoderationstatus",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/comments/setModerationStatus?banAuthor=%7B%7D&id=%7B%7D&moderationStatus=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Sets the moderation status of one or more comments"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7f73f982-697b-4f72-b296-1c3b5b813419"
            }
          ]
        }
      ]
    }
  ]
}
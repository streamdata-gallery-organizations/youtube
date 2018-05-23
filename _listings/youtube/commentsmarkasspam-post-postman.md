{
  "info": {
    "name": "Youtube Add Comments Mark as SPAM",
    "_postman_id": "4cec0c18-6206-413b-8247-b36674eea8d9",
    "description": "Expresses the caller's opinion that one or more comments should be flagged as spam.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "comments",
      "item": [
        {
          "id": "e9502834-9e3c-43f5-a167-9fc86aadb28e",
          "name": "postCommentsMarkasspam",
          "request": {
            "url": "http://www.googleapis.com/youtube/v1/comments/markAsSpam?id=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Expresses the caller's opinion that one or more comments should be flagged as spam"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8fa0eb24-23dc-4061-acb3-e9e8d8885ec8"
            }
          ]
        }
      ]
    }
  ]
}
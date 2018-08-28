{
  "info": {
    "name": "Victor Ops Get an organization's on-call users",
    "_postman_id": "0295a567-b5c3-4a75-9245-a232b4caee83",
    "description": "Get all on-call uesrs/teams for your organization.\n\nThis API may be called a maximum of 1 times per minute.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Oncall",
      "item": [
        {
          "id": "6a279200-a1d5-4f7f-a96f-4543944b6182",
          "name": "api_public.v1.oncall.current.get",
          "request": {
            "url": "http://api.victorops.com/api-public/v1/oncall/current?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get all on-call uesrs/teams for your organization.\n\nThis API may be called a maximum of 1 times per minute."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92b5b3ac-51ab-40bc-8139-969bbf0a1943"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Santander Bank Get ATMs",
    "_postman_id": "047011ab-7f1a-4a1a-a14e-c63c369d8ca3",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can provide multiple ATMs.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "atms",
      "item": [
        {
          "id": "1675a167-c5b2-4418-baba-06feb5879ae8",
          "name": "getATMS",
          "request": {
            "url": "http://openapi.santander.co.uk/open-banking/v2.1/atms/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint can contain multiple brands owned by a particular banking group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a688b56-9fd3-4f2c-8df9-b656401c1780"
            }
          ]
        }
      ]
    }
  ]
}
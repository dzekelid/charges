{
  "info": {
    "name": "Shopify Retrieving all one-time charges since a specified ID",
    "_postman_id": "ee120ba6-00c1-4943-9802-aca6b94dcbdc",
    "description": "Retrieving all one-time charges since a specified id.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Commerce",
      "item": [
        {
          "id": "de4ea9eb-49a8-45dc-b7d1-16f5cefc3065",
          "name": "getAdminApplicationCharges.json",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/admin/application_charges.json?since_id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Retrieving all one-time charges since a specified id."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d54c36ed-0cd9-4eb8-83ca-081f6d2c2683"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Stripe Get Charges Charge",
    "_postman_id": "a153a43c-b828-4041-a3b8-4e16a6db9f49",
    "description": "Retrieves the details of a charge that has previously been created. Supply the unique charge ID that was returned from your previous request, and Stripe will return the corresponding charge information. The same information is returned when creating or refunding the charge.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "charges",
      "item": [
        {
          "id": "361cc29c-bb01-400d-8f14-e37bfcde2b24",
          "name": "getChargesCharge",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.stripe.com",
              "path": [
                "v1",
                "charges/:charge"
              ],
              "query": [
                {
                  "key": "expand",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "charge",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the details of a charge that has previously been created"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c62ca7be-0323-4685-80c1-268cbe49d244"
            }
          ]
        }
      ]
    }
  ]
}
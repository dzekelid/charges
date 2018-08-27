{
  "info": {
    "name": "Stripe Get Charges Charge Dispute",
    "_postman_id": "1762360b-5dd1-4990-b44e-3fe63dab8e30",
    "description": "Get Charges, Charge, Dispute",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "charges",
      "item": [
        {
          "id": "bd082e37-a3bd-4f91-8dc1-b18bb0822e9b",
          "name": "getChargesChargeDispute",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.stripe.com",
              "path": [
                "v1",
                "charges/:charge/dispute"
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
            "description": "Get Charges, Charge, Dispute"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b23f049-2937-4601-8c8d-1d9da3a02d3f"
            }
          ]
        }
      ]
    }
  ]
}
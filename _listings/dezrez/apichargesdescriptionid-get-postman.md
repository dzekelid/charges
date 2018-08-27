{
  "info": {
    "name": "Dezrez ",
    "_postman_id": "6fee47bc-8f94-48a4-a752-665ffe890972",
    "description": ".",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Remove",
      "item": [
        {
          "id": "d2b6fe81-2b35-47f3-9f17-49618788ac1c",
          "name": "LettingsProgression_RemoveTenantChargesByroleIdBychargeIds",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/progression/lettings/:roleId/removetenantcharge"
              ],
              "query": [
                {
                  "key": "chargeIds",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "roleId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
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
            "description": "Remove charges from a tenant role."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "32ed4015-c5c6-4416-945d-ea758fc9f963"
            }
          ]
        }
      ]
    },
    {
      "name": "Folder",
      "item": [
        {
          "id": "29a4b3a4-6b0b-47bf-81ca-92502bcc9dde",
          "name": "ChargesDescription_GetByid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/ChargesDescription/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
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
            "description": "."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4d64d6b1-7e91-4f97-8717-2e78a6419f38"
            }
          ]
        }
      ]
    }
  ]
}
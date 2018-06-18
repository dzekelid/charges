---
swagger: "2.0"
x-collection-name: Etsy
x-complete: 1
info:
  title: Etsy
  description: bring-etsys-handmade-marketplace-and-community-into-your-apps-
  version: 1.0.0
host: openapi.etsy.com
basePath: /v2/private/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{user_id}/charges:
    get:
      summary: Get Users User Charges
      description: Retrieves a set of BillCharge objects associated to a User.
      operationId: getUsersUserCharges
      x-api-path-slug: usersuser-idcharges-get
      parameters:
      - in: query
        name: limit
        description: Bring Etsys handmade marketplace and community into your apps
      - in: query
        name: offset
        description: Bring Etsys handmade marketplace and community into your apps
      - in: path
        name: user_id
      responses:
        200:
          description: OK
      tags:
      - Users
      - Charges
---
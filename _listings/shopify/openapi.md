---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 1
info:
  title: Shopify API
  description: todo-add-description
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/application_charges.json:
    get:
      summary: Retrieving all one-time charges since a specified ID
      description: Retrieving all one-time charges since a specified id.
      operationId: getAdminApplicationCharges.json
      x-api-path-slug: adminapplication-charges-json-get
      parameters:
      - in: header
        name: Content-Type
      - in: query
        name: since_id
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieving
      - One-time
      - Charges
      - Since
      - Specified
      - ID
    post:
      summary: Create a new one-time application charge.
      description: Create a new one-time application charge..
      operationId: postAdminApplicationCharges.json
      x-api-path-slug: adminapplication-charges-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - One-time
      - Application
      - Charge
  /admin/application_charges/1.json:
    get:
      summary: Retrieve one-time application charge
      description: Retrieve one-time application charge.
      operationId: getAdminApplicationCharges1.json
      x-api-path-slug: adminapplication-charges1-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Retrieve
      - One-time
      - Application
      - Charge
  /admin/application_charges/675931192/activate.json:
    post:
      summary: Activate a one-time charge
      description: Activate a one-time charge.
      operationId: postAdminApplicationCharges675931192Activate.json
      x-api-path-slug: adminapplication-charges675931192activate-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Activate
      - One-time
      - Charge
  /admin/recurring_application_charges.json:
    post:
      summary: Create a new charge
      description: Create a new charge.
      operationId: postAdminRecurringApplicationCharges.json
      x-api-path-slug: adminrecurring-application-charges-json-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - New
      - Charge
---
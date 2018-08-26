---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 0
info:
  title: Shopify Retrieving all one-time charges since a specified ID
  description: Retrieving all one-time charges since a specified id.
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
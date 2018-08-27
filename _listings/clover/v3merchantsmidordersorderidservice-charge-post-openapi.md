---
swagger: "2.0"
x-collection-name: Clover
x-complete: 0
info:
  title: 'Clover '
  version: 1.0.0
  description: .
host: /merchants
basePath: https://api.clover.com
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/merchants/{mId}/default_service_charge:
    get:
      summary: Get default service charge for a merchant
      description: The Merchant's default service charge, set via the Setup App (https://www.clover.com/setupapp).
      operationId: GetDefaultServiceCharge
      x-api-path-slug: v3merchantsmiddefault-service-charge-get
      parameters:
      - in: path
        name: mId
        description: Merchant Id
      responses:
        200:
          description: OK
      tags:
      - Merchants
      - Default
      - Service
      - Charge
  /v3/merchants/{mId}/orders/{orderId}/service_charge/:
    post:
      summary: ""
      description: .
      operationId: ApplyServiceCharge
      x-api-path-slug: v3merchantsmidordersorderidservice-charge-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: mId
        description: Merchant Id
      - in: path
        name: orderId
        description: Order Id
      responses:
        200:
          description: OK
      tags:
      - Merchants
      - Orders
      - OrderId
      - Service
      - Charge
  /v3/merchants/{mId}/orders/{orderId}/service_charge/{chargeId}:
    delete:
      summary: Remove service charge from an order
      description: Remove service charge from an order.
      operationId: RemoveServiceCharge
      x-api-path-slug: v3merchantsmidordersorderidservice-chargechargeid-delete
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: chargeId
        description: Service Charge Id
      - in: path
        name: mId
        description: Merchant Id
      - in: path
        name: orderId
        description: Order Id
      responses:
        200:
          description: OK
      tags:
      - Merchants
      - Orders
      - OrderId
      - Service
      - Charge
      - ChargeId
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
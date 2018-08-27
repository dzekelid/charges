---
swagger: "2.0"
x-collection-name: Transport for London Unified
x-complete: 0
info:
  title: Transport for London Unified Occupancy  Charge Connector s
  description: Gets the occupancy for a charge connectors with a given id (sourcesystemplaceid).
  version: v1
host: api.tfl.gov.uk
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Occupancy/ChargeConnector:
    get:
      summary: Occupancy  Charge Connector
      description: Gets the occupancy for all charge connectors.
      operationId: Occupancy_GetAllChargeConnectorStatus
      x-api-path-slug: occupancychargeconnector-get
      responses:
        200:
          description: OK
      tags:
      - Occupancy
      - ""
      - Charge
      - Connector
  /Occupancy/ChargeConnector/{ids}:
    get:
      summary: Occupancy  Charge Connector s
      description: Gets the occupancy for a charge connectors with a given id (sourcesystemplaceid).
      operationId: Occupancy_GetChargeConnectorStatus
      x-api-path-slug: occupancychargeconnectorids-get
      parameters:
      - in: path
        name: ids
      responses:
        200:
          description: OK
      tags:
      - Occupancy
      - ""
      - Charge
      - Connector
      - S
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
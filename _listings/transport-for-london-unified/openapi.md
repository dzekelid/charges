swagger: "2.0"
x-collection-name: Transport for London Unified
x-complete: 1
info:
  title: Transport for London Unified
  description: our-unified-api-brings-together-data-across-all-modes-of-transport-into-a-single-restful-api--this-api-provides-access-to-the-most-highly-requested-realtime-and-status-infomation-across-all-the-modes-of-transport-in-a-single-and-consistent-way--access-to-the-developer-documentation-is-available-at-httpsapi-tfl-gov-uk
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
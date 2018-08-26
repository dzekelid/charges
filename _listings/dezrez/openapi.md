---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/progression/lettings/{roleId}/removetenantcharge:
    delete:
      summary: Remove charges from a tenant role
      description: Remove charges from a tenant role.
      operationId: LettingsProgression_RemoveTenantChargesByroleIdBychargeIds
      x-api-path-slug: apiprogressionlettingsroleidremovetenantcharge-delete
      parameters:
      - in: query
        name: chargeIds
        description: The ids of the charges to remove
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: roleId
        description: The tenant role id
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Charges
      - From
      - Tenant
      - Role
  /api/ChargesDescription/{id}:
    get:
      summary: ""
      description: .
      operationId: ChargesDescription_GetByid
      x-api-path-slug: apichargesdescriptionid-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - ""
---
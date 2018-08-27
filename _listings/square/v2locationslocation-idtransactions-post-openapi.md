---
swagger: "2.0"
x-collection-name: Square
x-complete: 0
info:
  title: Square Connect API Charge
  description: |-
    Charges a card represented by a card nonce or a customer's card on file.

    Your request to this endpoint must include _either_:

    - A value for the `card_nonce` parameter (to charge a card nonce generated
    with the `SqPaymentForm`)
    - Values for the `customer_card_id` and `customer_id` parameters (to charge
    a customer's card on file)

    In order for an e-commerce payment to potentially qualify for
    [Square chargeback protection](https://squareup.com/help/article/5394), you
    _must_ provide values for the following parameters in your request:

    - `buyer_email_address`
    - At least one of `billing_address` or `shipping_address`

    When this response is returned, the amount of Square's processing fee might not yet be
    calculated. To obtain the processing fee, wait about ten seconds and call
    [RetrieveTransaction](#endpoint-retrievetransaction). See the `processing_fee_money`
    field of each [Tender included](#type-tender) in the transaction.
  termsOfService: https://connect.squareup.com/tos
  contact:
    name: Square Developer Platform
    url: https://squareup.com/developers
    email: developers@squareup.com
  version: "2.0"
host: connect.squareup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/locations/{location_id}/transactions:
    post:
      summary: Charge
      description: |-
        Charges a card represented by a card nonce or a customer's card on file.

        Your request to this endpoint must include _either_:

        - A value for the `card_nonce` parameter (to charge a card nonce generated
        with the `SqPaymentForm`)
        - Values for the `customer_card_id` and `customer_id` parameters (to charge
        a customer's card on file)

        In order for an e-commerce payment to potentially qualify for
        [Square chargeback protection](https://squareup.com/help/article/5394), you
        _must_ provide values for the following parameters in your request:

        - `buyer_email_address`
        - At least one of `billing_address` or `shipping_address`

        When this response is returned, the amount of Square's processing fee might not yet be
        calculated. To obtain the processing fee, wait about ten seconds and call
        [RetrieveTransaction](#endpoint-retrievetransaction). See the `processing_fee_money`
        field of each [Tender included](#type-tender) in the transaction.
      operationId: Charge
      x-api-path-slug: v2locationslocation-idtransactions-post
      parameters:
      - in: header
        name: Authorization
        description: The value to provide in the Authorization header ofyour request
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: location_id
        description: The ID of the location to associate the created transaction with
      responses:
        200:
          description: OK
      tags:
      - Charge
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
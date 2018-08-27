---
name: Square
x-slug: square
description: Square helps millions of sellers run their business- from secure credit
  card processing to point of sale solutions. Get paid faster with Square and sign
  up today!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
x-kinRank: "9"
x-alexaRank: "2433"
tags: Charges
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/square/apis.md
specificationVersion: "0.14"
apis:
- name: Square Connect - Charge
  x-api-slug: v2locationslocation-idtransactions-post
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com//
  tags: Payments, Credit Cards, Commerce, Stack Network, Financial Services, Mobile,
    Technology, internet, Payments, Relative Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/square/v2locationslocation-idtransactions-post-openapi.md
- name: Square Connect - Charge
  x-api-slug: v2locationslocation-idtransactions-post
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com//
  tags: Payments, Credit Cards, Commerce, Stack Network, Financial Services, Mobile,
    Technology, internet, Payments, Relative Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/square/v2locationslocation-idtransactions-post-openapi.md
- name: Square Connect - Charge
  x-api-slug: v2locationslocation-idtransactions-post
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com//
  tags: Payments, Credit Cards, Commerce, Stack Network, Financial Services, Mobile,
    Technology, internet, Payments, Relative Data, Service API, Relative StreamRank,
    Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/square/v2locationslocation-idtransactions-post-openapi.md
x-common:
- type: x-website
  url: http://square.com
- type: x-api-gallery
  url: http://spreaker.api.gallery.streamdata.io
- type: x-api-stack
  url: http://square.stack.network
- type: x-base
  url: https://connect.squareup.com
- type: x-crunchbase
  url: http://www.crunchbase.com/company/square
- type: x-crunchbase
  url: https://crunchbase.com/organization/square
- type: x-developer
  url: https://connect.squareup.com/
- type: x-email
  url: press@squareup.com
- type: x-email
  url: security@squareup.com
- type: x-email
  url: lawenforcement@squareup.com
- type: x-email
  url: redemption@squareup.com
- type: x-email
  url: privacy@squareup.com
- type: x-email
  url: community@squareup.com
- type: x-email
  url: noreply@messaging.squareup.com
- type: x-email
  url: ir@squareup.com
- type: x-email
  url: takedowns@squareup.com
- type: x-github
  url: https://github.com/square
- type: x-linkedin
  url: https://www.linkedin.com/company/square--/
- type: x-twitter
  url: https://twitter.com/Square
- type: x-website
  url: http://squareup.com
- type: x-website
  url: https://squareup.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
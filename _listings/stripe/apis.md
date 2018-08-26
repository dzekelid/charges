---
name: Stripe
x-slug: stripe
description: Online payment processing for internet businesses. Stripe is a suite
  of payment APIs that powers commerce for online businesses of all sizes, including
  fraud prevention, and subscription management. Use Stripes payment platform to accept
  and process p...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
x-kinRank: "10"
x-alexaRank: "1914"
tags: Charges
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/apis.md
specificationVersion: "0.14"
apis:
- name: Stripe - Get Charges
  x-api-slug: charges-get
  description: Returns a list of charges you???ve previously created. The charges
    are returned in sorted order, with the most recent charges appearing first.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/charges-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/charges-get-openapi.md
- name: Stripe - Get Charges Charge
  x-api-slug: chargescharge-get
  description: Retrieves the details of a charge that has previously been created.
    Supply the unique charge ID that was returned from your previous request, and
    Stripe will return the corresponding charge information. The same information
    is returned when creating or refunding the charge.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargescharge-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargescharge-get-openapi.md
- name: Stripe - Get Charges Charge Dispute
  x-api-slug: chargeschargedispute-get
  description: Get Charges, Charge, Dispute
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargedispute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargedispute-get-openapi.md
- name: Stripe - Get Charges Charge Refunds
  x-api-slug: chargeschargerefunds-get
  description: You can see a list of the refunds belonging to a specific charge. Note
    that the 10 most recent refunds are always available by default on the charge
    object. If you need more than those 10, you can use this API method and the limit
    and starting_after parameters to page through additional refunds.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefunds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefunds-get-openapi.md
- name: Stripe - Get Charges Charge Refunds Refund
  x-api-slug: chargeschargerefundsrefund-get
  description: Get Charges, Charge, Refunds, Refund
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefundsrefund-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefundsrefund-get-openapi.md
- name: Stripe - Get Charges Charge
  x-api-slug: chargescharge-get
  description: Retrieves the details of a charge that has previously been created.
    Supply the unique charge ID that was returned from your previous request, and
    Stripe will return the corresponding charge information. The same information
    is returned when creating or refunding the charge.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargescharge-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargescharge-get-openapi.md
- name: Stripe - Get Charges Charge Dispute
  x-api-slug: chargeschargedispute-get
  description: Get Charges, Charge, Dispute
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargedispute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargedispute-get-openapi.md
- name: Stripe - Get Charges Charge Refunds
  x-api-slug: chargeschargerefunds-get
  description: You can see a list of the refunds belonging to a specific charge. Note
    that the 10 most recent refunds are always available by default on the charge
    object. If you need more than those 10, you can use this API method and the limit
    and starting_after parameters to page through additional refunds.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefunds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefunds-get-openapi.md
- name: Stripe - Get Charges Charge Refunds Refund
  x-api-slug: chargeschargerefundsrefund-get
  description: Get Charges, Charge, Refunds, Refund
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefundsrefund-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefundsrefund-get-openapi.md
- name: Stripe - Get Charges Charge
  x-api-slug: chargescharge-get
  description: Retrieves the details of a charge that has previously been created.
    Supply the unique charge ID that was returned from your previous request, and
    Stripe will return the corresponding charge information. The same information
    is returned when creating or refunding the charge.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargescharge-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargescharge-get-openapi.md
- name: Stripe - Get Charges Charge Dispute
  x-api-slug: chargeschargedispute-get
  description: Get Charges, Charge, Dispute
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargedispute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargedispute-get-openapi.md
- name: Stripe - Get Charges Charge Refunds
  x-api-slug: chargeschargerefunds-get
  description: You can see a list of the refunds belonging to a specific charge. Note
    that the 10 most recent refunds are always available by default on the charge
    object. If you need more than those 10, you can use this API method and the limit
    and starting_after parameters to page through additional refunds.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefunds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefunds-get-openapi.md
- name: Stripe - Get Charges Charge Refunds Refund
  x-api-slug: chargeschargerefundsrefund-get
  description: Get Charges, Charge, Refunds, Refund
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/254-stripe.jpg
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Billing, Finance, Payments, Payments, Stripe Stack, Imports, Change Log Example,
    Stack Network, Stack, SaaS, Invoices, Payments, Relative Data, Service API, Relative
    StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefundsrefund-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefundsrefund-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://stride.api.gallery.streamdata.io
- type: x-api-stack
  url: http://stripe.stack.network
- type: x-base
  url: https://api.stripe.com/
- type: x-blog
  url: https://stripe.com/blog
- type: x-blog-rss
  url: https://stripe.com/blog/feed.rss
- type: x-change-log
  url: https://stripe.com/docs/upgrades
- type: x-crunchbase
  url: http://www.crunchbase.com/company/stripe
- type: x-crunchbase
  url: https://crunchbase.com/organization/stripe
- type: x-email
  url: info@stripe.com
- type: x-email
  url: privacy@stripe.com
- type: x-email
  url: atlas@stripe.com
- type: x-email
  url: notices@stripe.com
- type: x-email
  url: jane.diaz@stripe.com
- type: x-email
  url: nonprofit@stripe.com
- type: x-email
  url: support@stripe.com
- type: x-email
  url: dpo@stripe.com
- type: x-github
  url: https://github.com/stripe
- type: x-linkedin
  url: https://www.linkedin.com/company/stripe/
- type: x-pricing
  url: https://stripe.com/us/pricing
- type: x-twitter
  url: https://twitter.com/stripe
- type: x-website
  url: https://stripe.com/
- type: x-website
  url: http://stripe.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
---
name: Stripe
x-slug: stripe
description: 'Stripe is a simple, developer-friendly way to accept payments online.
  They believe that enabling transactions on the web is a problem rooted in code,
  not finance, and they want to help put more websites in business. '
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
x-kinRank: "10"
x-alexaRank: ""
tags: Charges
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/apis.md
specificationVersion: "0.14"
apis:
- name: Stripe Get Charges
  x-api-slug: stripe
  description: "Returns a list of charges you\u2019ve previously created. The charges
    are returned in sorted order, with the most recent charges appearing first."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges
  tags: Charges
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/charges-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/charges-get-openapi.md
- name: Stripe Add Charges
  x-api-slug: stripe
  description: Post Charges
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges
  tags: Charges
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/charges-post-openapi.md
- name: Stripe Get Charges Charge
  x-api-slug: stripe
  description: Retrieves the details of a charge that has previously been created.
    Supply the unique charge ID that was returned from your previous request, and
    Stripe will return the corresponding charge information. The same information
    is returned when creating or refunding the charge.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}
  tags: Charges, Charge
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargescharge-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargescharge-get-openapi.md
- name: Stripe Add Charges Charge
  x-api-slug: stripe
  description: Updates the specified charge by setting the values of the parameters
    passed. Any parameters not provided will be left unchanged.This request accepts
    only the customer, description, fraud_details, metadata, receipt_email, and shipping
    arguments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}
  tags: Charges, Charge
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargescharge-post-openapi.md
- name: Stripe Add Charges Charge Capture
  x-api-slug: stripe
  description: Capture the payment of an existing, uncaptured, charge. This is the
    second half of the two-step payment flow, where first you created a charge with
    the capture option set to false.Uncaptured payments expire exactly seven days
    after they are created. If they are not captured by that point in time, they will
    be marked as refunded and will no longer be capturable.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/capture
  tags: Charges, Charge, Capture
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargecapture-post-openapi.md
- name: Stripe Get Charges Charge Dispute
  x-api-slug: stripe
  description: Get Charges, Charge, Dispute
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/dispute
  tags: Charges, Charge, Dispute
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargedispute-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargedispute-get-openapi.md
- name: Stripe Add Charges Charge Dispute
  x-api-slug: stripe
  description: Post Charges, Charge, Dispute
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/dispute
  tags: Charges, Charge, Dispute
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargedispute-post-openapi.md
- name: Stripe Add Charges Charge Dispute Close
  x-api-slug: stripe
  description: Post Charges, Charge, Dispute, Close
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/dispute/close
  tags: Charges, Charge, Dispute, Close
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargedisputeclose-post-openapi.md
- name: Stripe Add Charges Charge Refund
  x-api-slug: stripe
  description: Post Charges, Charge, Refund
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/refund
  tags: Charges, Charge, Refund
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefund-post-openapi.md
- name: Stripe Get Charges Charge Refunds
  x-api-slug: stripe
  description: You can see a list of the refunds belonging to a specific charge. Note
    that the 10 most recent refunds are always available by default on the charge
    object. If you need more than those 10, you can use this API method and the limit
    and starting_after parameters to page through additional refunds.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/refunds
  tags: Charges, Charge, Refunds
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefunds-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefunds-get-openapi.md
- name: Stripe Add Charges Charge Refunds
  x-api-slug: stripe
  description: Post Charges, Charge, Refunds
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/refunds
  tags: Charges, Charge, Refunds
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefunds-post-openapi.md
- name: Stripe Get Charges Charge Refunds Refund
  x-api-slug: stripe
  description: Get Charges, Charge, Refunds, Refund
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/refunds/{refund}
  tags: Charges, Charge, Refunds, Refund
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefundsrefund-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefundsrefund-get-openapi.md
- name: Stripe Add Charges Charge Refunds Refund
  x-api-slug: stripe
  description: Post Charges, Charge, Refunds, Refund
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1///charges/{charge}/refunds/{refund}
  tags: Charges, Charge, Refunds, Refund
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/chargeschargerefundsrefund-post-openapi.md
- name: Stripe
  x-api-slug: stripe
  description: Web and mobile payments, built for developers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/stripe-black.png
  humanURL: https://stripe.com/
  baseURL: https://api.stripe.com/v1/
  tags: Charges
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/charges/master/_listings/stripe/openapi.md
x-common:
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
- type: x-github
  url: https://github.com/stripe
- type: x-pricing
  url: https://stripe.com/us/pricing
- type: x-twitter
  url: https://twitter.com/stripe
- type: x-website
  url: https://stripe.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
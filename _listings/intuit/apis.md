---
name: Intuit
x-slug: intuit
description: See how the power of Intuit Giants can work for you by joining the over
  46 million people already using TurboTax, QuickBooks and Mint to power their financial
  prosperity.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/9544-intuit.jpg
x-kinRank: "8"
x-alexaRank: "263"
tags: Credit
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/credit/master/_listings/intuit/apis.md
specificationVersion: "0.14"
apis:
- name: QuickBooks Online V3 API - Post Credit Memo
  x-api-slug: creditmemo-post
  description: |-
    Update a credit memo
    Method : POST
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/9544-intuit.jpg
  humanURL: https://intuit.com
  baseURL: https://DefaultParameterValue//v3/company/DefaultParameterValue
  tags: Finance, Accounting, Orange Report Financial, Finance, Accounting, Stack Network,
    Stack, Financial Services, SaaS, Technology, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/credit/master/_listings/intuit/creditmemo-post-openapi.md
- name: QuickBooks Online V3 API - Post Vendor Credit
  x-api-slug: vendorcredit-post
  description: "Delete a vendorcredit object by Id\nMethod : POST\n\nSample response
    body \n\n{\n  \"VendorCredit\": {\n    \"domain\": \"QBO\",\n    \"status\": \"Deleted\",\n
    \   \"Id\": \"185\"\n  },\n  \"time\": \"2016-09-02T03:14:13.909-07:00\"\n}"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/9544-intuit.jpg
  humanURL: https://intuit.com
  baseURL: https://DefaultParameterValue//v3/company/DefaultParameterValue
  tags: Finance, Accounting, Orange Report Financial, Finance, Accounting, Stack Network,
    Stack, Financial Services, SaaS, Technology, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/credit/master/_listings/intuit/vendorcredit-post-openapi.md
- name: QuickBooks Online V3 API - Get Credit Memo
  x-api-slug: creditmemo160-get
  description: |-
    Read a credit memo by Id
    Method : GET
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/9544-intuit.jpg
  humanURL: https://intuit.com
  baseURL: https://DefaultParameterValue//v3/company/DefaultParameterValue
  tags: Finance, Accounting, Orange Report Financial, Finance, Accounting, Stack Network,
    Stack, Financial Services, SaaS, Technology, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/credit/master/_listings/intuit/creditmemo160-get-openapi.md
- name: QuickBooks Online V3 API - Get Vendor Credit
  x-api-slug: vendorcredit185-get
  description: |-
    Read a vendorcredit object by Id
    Method : GET

    Please change the VendorCredit it from 165 to a valid VendorCredit objectId which exists in your QBO account
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/9544-intuit.jpg
  humanURL: https://intuit.com
  baseURL: https://DefaultParameterValue//v3/company/DefaultParameterValue
  tags: Finance, Accounting, Orange Report Financial, Finance, Accounting, Stack Network,
    Stack, Financial Services, SaaS, Technology, API Provider, Profiles, Relative
    Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/credit/master/_listings/intuit/vendorcredit185-get-openapi.md
x-common:
- type: x-postman-collection
  url: https://www.getpostman.com/collections/554420530884cde6b794
- type: x-api-gallery
  url: http://intrinio.api.gallery.streamdata.io
- type: x-api-stack
  url: http://intuit.stack.network
- type: x-base
  url: https://appcenter.intuit.com/api/
- type: x-blog
  url: https://developer.intuit.com/blog
- type: x-blog-rss
  url: https://developer.intuit.com/blog/feed
- type: x-crunchbase
  url: https://crunchbase.com/organization/intuit
- type: x-developer
  url: https://developer.intuit.com/
- type: x-email
  url: copyright@intuit.com
- type: x-email
  url: spoof@intuit.com
- type: x-github
  url: https://github.com/IntuitDeveloperRelations
- type: x-partners
  url: https://developer.intuit.com/partnerprogram
- type: x-road-map
  url: https://developer.intuit.com/blog/2013/12/19/2014-roadmap-and-migration-dates-for-existing-developers
- type: x-twitter
  url: https://twitter.com/Intuit
- type: x-twitter
  url: https://twitter.com/intuitdev
- type: x-website
  url: https://intuit.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
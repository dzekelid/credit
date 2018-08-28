---
swagger: "2.0"
x-collection-name: Intuit
x-complete: 0
info:
  title: QuickBooks Online V3 API Get Vendor Credit
  description: |-
    Read a vendorcredit object by Id
    Method : GET

    Please change the VendorCredit it from 165 to a valid VendorCredit objectId which exists in your QBO account
  version: 1.0.0
host: DefaultParameterValue
basePath: /v3/company/DefaultParameterValue
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /creditmemo:
    post:
      summary: Post Credit Memo
      description: |-
        Update a credit memo
        Method : POST
      operationId: postCreditmemo
      x-api-path-slug: creditmemo-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: query
        name: minorversion
      - in: header
        name: User-Agent
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Accounting
      - Credit
      - Memo
  /vendorcredit:
    post:
      summary: Post Vendor Credit
      description: "Delete a vendorcredit object by Id\nMethod : POST\n\nSample response
        body \n\n{\n  \"VendorCredit\": {\n    \"domain\": \"QBO\",\n    \"status\":
        \"Deleted\",\n    \"Id\": \"185\"\n  },\n  \"time\": \"2016-09-02T03:14:13.909-07:00\"\n}"
      operationId: postVendorcredit
      x-api-path-slug: vendorcredit-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: query
        name: operation
      - in: header
        name: User-Agent
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Accounting
      - Vendor
      - Credit
  /creditmemo/160:
    get:
      summary: Get Credit Memo
      description: |-
        Read a credit memo by Id
        Method : GET
      operationId: getCreditmemo160
      x-api-path-slug: creditmemo160-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: minorversion
      - in: header
        name: User-Agent
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Accounting
      - Credit
      - Memo
  /vendorcredit/185:
    get:
      summary: Get Vendor Credit
      description: |-
        Read a vendorcredit object by Id
        Method : GET

        Please change the VendorCredit it from 165 to a valid VendorCredit objectId which exists in your QBO account
      operationId: getVendorcredit185
      x-api-path-slug: vendorcredit185-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: minorversion
      - in: header
        name: User-Agent
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Accounting
      - Vendor
      - Credit
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
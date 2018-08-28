---
swagger: "2.0"
x-collection-name: Clover
x-complete: 0
info:
  title: Clover Get a single credit
  version: 1.0.0
  description: Get a single credit.
host: /merchants
basePath: https://api.clover.com
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/merchants/{mId}/credit_refunds:
    get:
      summary: Get a list of credit refunds
      description: Get a list of credit refunds.
      operationId: GetCreditRefunds
      x-api-path-slug: v3merchantsmidcredit-refunds-get
      parameters:
      - in: query
        name: expand
        description: 'Expandable fields: [credit, germanInfo, appTracking]'
      - in: path
        name: mId
        description: Merchant Id
      responses:
        200:
          description: OK
      tags:
      - Merchants
      - Credit
      - Refunds
  /v3/merchants/{mId}/credit_refunds/{crId}:
    get:
      summary: Get a credit refund
      description: Get a credit refund.
      operationId: GetCreditRefund
      x-api-path-slug: v3merchantsmidcredit-refundscrid-get
      parameters:
      - in: path
        name: crId
      - in: query
        name: expand
        description: 'Expandable fields: [credit, germanInfo, appTracking]'
      - in: path
        name: mId
        description: Merchant Id
      responses:
        200:
          description: OK
      tags:
      - Merchants
      - Credit
      - Refunds
      - CrId
  /v3/merchants/{mId}/credits:
    get:
      summary: Get a list of credits
      description: Get a list of credits.
      operationId: GetCredits
      x-api-path-slug: v3merchantsmidcredits-get
      parameters:
      - in: query
        name: expand
        description: 'Expandable fields: [dccInfo, germanInfo, appTracking, tender,
          employee, cardTransaction, order, taxRates]'
      - in: query
        name: filter
        description: 'Filter fields: [device'
      - in: path
        name: mId
        description: Merchant Id
      responses:
        200:
          description: OK
      tags:
      - Merchants
      - Credits
  /v3/merchants/{mId}/credits/{cId}:
    get:
      summary: Get a single credit
      description: Get a single credit.
      operationId: GetCredit
      x-api-path-slug: v3merchantsmidcreditscid-get
      parameters:
      - in: path
        name: cId
      - in: query
        name: expand
        description: 'Expandable fields: [dccInfo, germanInfo, appTracking, tender,
          employee, cardTransaction, order, taxRates]'
      - in: path
        name: mId
        description: Merchant Id
      responses:
        200:
          description: OK
      tags:
      - Merchants
      - Credits
      - CId
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
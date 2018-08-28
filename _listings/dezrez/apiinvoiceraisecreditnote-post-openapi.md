---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Raise a credit note against invoice items on an invoice
  version: 1.0.0
  description: Raise a credit note against invoice items on an invoice.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/invoice/raisecreditnote:
    post:
      summary: Raise a credit note against invoice items on an invoice
      description: Raise a credit note against invoice items on an invoice.
      operationId: Invoice_RaiseCreditNoteBycreditNoteDataContract
      x-api-path-slug: apiinvoiceraisecreditnote-post
      parameters:
      - in: body
        name: creditNoteDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Raise
      - Credit
      - Note
      - Against
      - Invoice
      - Items
      - "On"
      - Invoice
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
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
---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 1
info:
  title: Wallet_Api
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/FormatCreditVouchersContent:
    post:
      summary: Add API Formatcreditvoucherscontent
      description: Add api formatcreditvoucherscontent.
      operationId: ApiFormatCreditVouchersContentPost
      x-api-path-slug: apiformatcreditvoucherscontent-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Formatcreditvoucherscontent
---
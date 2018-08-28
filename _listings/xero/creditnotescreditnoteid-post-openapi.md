---
swagger: "2.0"
x-collection-name: Xero
x-complete: 0
info:
  title: Clarity Accounting Post Creditnotes Creditnote
  description: Post creditnotes creditnote.
  contact:
    name: Xero Developer Team
    url: https://developer.xero.com
  version: "2.0"
host: api.xero.com
basePath: /api.xro/2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /CreditNotes/{CreditNoteID}:
    get:
      summary: Get Creditnotes Creditnote
      description: Get creditnotes creditnote.
      operationId: getCreditnotesCreditnote
      x-api-path-slug: creditnotescreditnoteid-get
      parameters:
      - in: path
        name: CreditNoteID
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
    post:
      summary: Post Creditnotes Creditnote
      description: Post creditnotes creditnote.
      operationId: postCreditnotesCreditnote
      x-api-path-slug: creditnotescreditnoteid-post
      parameters:
      - in: path
        name: CreditNoteID
      - in: body
        name: CreditNotes
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
    x-related-model:
      summary: X-related-model Creditnotes Creditnote
      description: X-related-model creditnotes creditnote.
      operationId: x-related-modelCreditnotesCreditnote
      x-api-path-slug: creditnotescreditnoteid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
  /CreditNotes/{CreditNoteID}/Allocations:
    put:
      summary: Put Creditnotes Creditnote Allocations
      description: Put creditnotes creditnote allocations.
      operationId: putCreditnotesCreditnoteAllocations
      x-api-path-slug: creditnotescreditnoteidallocations-put
      parameters:
      - in: body
        name: Allocations
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: CreditNoteID
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
      - Ocations
    x-related-model:
      summary: X-related-model Creditnotes Creditnote Allocations
      description: X-related-model creditnotes creditnote allocations.
      operationId: x-related-modelCreditnotesCreditnoteAllocations
      x-api-path-slug: creditnotescreditnoteidallocations-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
      - Ocations
  /CreditNotes/{CreditNoteID}/Attachments:
    get:
      summary: Get Creditnotes Creditnote Attachments
      description: Get creditnotes creditnote attachments.
      operationId: getCreditnotesCreditnoteAttachments
      x-api-path-slug: creditnotescreditnoteidattachments-get
      parameters:
      - in: path
        name: CreditNoteID
        description: The Xero generated unique identifier for a CreditNote
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
      - Attachments
  /CreditNotes/{CreditNoteID}/Attachments/{FileName}:
    get:
      summary: Get Creditnotes Creditnote Attachments Filename
      description: Get creditnotes creditnote attachments filename.
      operationId: getCreditnotesCreditnoteAttachmentsFilename
      x-api-path-slug: creditnotescreditnoteidattachmentsfilename-get
      parameters:
      - in: path
        name: CreditNoteID
        description: The Xero generated unique identifier for a CreditNote
      - in: path
        name: FileName
        description: The filename of the attachment to be downloaded
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
      - Attachments
      - FileName
    post:
      summary: Post Creditnotes Creditnote Attachments Filename
      description: Post creditnotes creditnote attachments filename.
      operationId: postCreditnotesCreditnoteAttachmentsFilename
      x-api-path-slug: creditnotescreditnoteidattachmentsfilename-post
      parameters:
      - in: body
        name: Content
        description: The raw content of the file to be uploaded
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: CreditNoteID
        description: The Xero generated unique identifier for a CreditNote
      - in: path
        name: FileName
        description: The filename of the attachment being uploaded
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
      - CreditNoteID
      - Attachments
      - FileName
  /CreditNotes:
    get:
      summary: Get Creditnotes
      description: Get creditnotes.
      operationId: getCreditnotes
      x-api-path-slug: creditnotes-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
    post:
      summary: Post Creditnotes
      description: Post creditnotes.
      operationId: postCreditnotes
      x-api-path-slug: creditnotes-post
      parameters:
      - in: body
        name: CreditNotes
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
    put:
      summary: Put Creditnotes
      description: Put creditnotes.
      operationId: putCreditnotes
      x-api-path-slug: creditnotes-put
      parameters:
      - in: body
        name: CreditNotes
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
    x-related-model:
      summary: X-related-model Creditnotes
      description: X-related-model creditnotes.
      operationId: x-related-modelCreditnotes
      x-api-path-slug: creditnotes-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - CreditNotes
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
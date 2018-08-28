---
swagger: "2.0"
x-collection-name: iSendPro Telecom
x-complete: 0
info:
  title: API i Send Pro Interrogation credit
  description: Retourne le credit existant associe au compte.
  termsOfService: https://www.isendpro.com/cgv.php
  contact:
    name: iSendPro Support Team
    url: https://www.isendpro.com/
    email: support@isendpro.com
  version: 1.0.0
host: apirest.isendpro.com
basePath: /cgi-bin
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /credit:
    get:
      summary: Interrogation credit
      description: Retourne le credit existant associe au compte.
      operationId: getCredit
      x-api-path-slug: credit-get
      parameters:
      - in: query
        name: credit
        description: Type de reponse demande, 1 pour euro, 2 pour euro + estimation
          quantit
      - in: query
        name: keyid
        description: Cl API
      responses:
        200:
          description: OK
      tags:
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
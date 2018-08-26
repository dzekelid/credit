---
swagger: "2.0"
x-collection-name: Pingdom
x-complete: 0
info:
  title: Credits API Get Credits List
  description: Returns information about remaining checks, SMS credits and SMS auto-refill
    status.
  version: 1.0.0
host: api.pingdom.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? |2-

        /api/{version}/credits
  : ? |2-

          get
    : summary: Get Credits List
      description: Returns information about remaining checks, SMS credits and SMS
        auto-refill status.
      operationId: get-credits-list
      x-api-path-slug: apiversioncredits-get
      responses:
        200:
          description: OK
      tags:
      - Credits
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
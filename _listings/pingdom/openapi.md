swagger: "2.0"
x-collection-name: Pingdom
x-complete: 1
info:
  title: Traceroute API
  description: the-traceroute-api-
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
host: api.pingdom.com
basePath: /
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
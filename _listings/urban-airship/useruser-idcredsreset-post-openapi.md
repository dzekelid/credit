---
swagger: "2.0"
x-collection-name: Urban Airship
x-complete: 0
info:
  title: Urban Airship Post User User Creds Reset
  description: Changes the password of an user.
  version: v3
host: go.urbanairship.com
basePath: /api/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/{user_id}/creds/reset:
    post:
      summary: Post User User Creds Reset
      description: Changes the password of an user.
      operationId: user.user_id.creds.reset.post
      x-api-path-slug: useruser-idcredsreset-post
      parameters:
      - in: header
        name: Content-Type
        description: Content type
      - in: query
        name: Content-Type
        description: Content type
      - in: query
        name: user_id
        description: The user ID
      - in: path
        name: user_id
      responses:
        200:
          description: OK
      tags:
      - User
      - User
      - Id
      - Creds
      - Reset
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
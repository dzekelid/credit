swagger: "2.0"
x-collection-name: AMEE
x-complete: 1
info:
  title: AMEE WRI Aqueduct API
  version: 1.0.0
host: api.roaring.io
basePath: /company/1.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /company-credit-decision:
    get:
      summary: Get Company Credit Decision
      description: Get company credit decision.
      operationId: getCompanyCreditDecision
      x-api-path-slug: companycreditdecision-get
      parameters:
      - in: query
        name: companyId
        description: Company identification for the company
      - in: query
        name: countryCode
        description: Country code for the company
      - in: query
        name: template
        description: Template for credit decision
      responses:
        200:
          description: OK
      tags:
      - Company
      - Credit
      - Decision
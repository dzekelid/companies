---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite Fact Set Estimates
  description: this-web-service-provides-global-estimate-data
  version: 1.0.0
host: factsetestimates.xignite.com
basePath: xFactSetEstimates.json/XigniteFactSetEstimates
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ListCompanies:
    post:
      summary: List Companies
      description: List Symbols
      operationId: ListCompanies
      x-api-path-slug: listcompanies-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - List
      - Companies
---
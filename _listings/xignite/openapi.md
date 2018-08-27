swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite VWAP
  description: provides-delayed-and-historical-volumeweightedaverage-price-vwap-information-
  version: 1.0.0
host: www.xignite.com
basePath: xVWAP.json/XigniteVWAP
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ListCompanies:
    get:
      summary: List Companies
      description: List Symbols
      operationId: ListCompanies
      x-api-path-slug: listcompanies-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - List
      - Companies
  /GetIssuerByCompanyIdentifier:
    get:
      summary: Get Issuer By Company Identifier
      description: Get a issuer by the company identifier.
      operationId: GetIssuerByCompanyIdentifier
      x-api-path-slug: getissuerbycompanyidentifier-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Issuer
      - Company
      - Identifier
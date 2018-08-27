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
  /api/group/{id}/addpreferredcompany:
    post:
      summary: Add a preferred company to a group
      description: Add a preferred company to a group.
      operationId: Group_AddPreferredCompanyByidBycompanyIdBypreferredContactId
      x-api-path-slug: apigroupidaddpreferredcompany-post
      parameters:
      - in: query
        name: companyId
      - in: path
        name: id
      - in: query
        name: preferredContactId
        description: The person id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Preferred
      - Company
      - To
      - Group
  /api/group/{id}/removepreferredcompany:
    post:
      summary: Remove a preferred company to a group
      description: Remove a preferred company to a group.
      operationId: Group_RemovePreferredCompanyByidBycompanyId
      x-api-path-slug: apigroupidremovepreferredcompany-post
      parameters:
      - in: query
        name: companyId
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Remove
      - Preferred
      - Company
      - To
      - Group
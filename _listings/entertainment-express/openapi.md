---
swagger: "2.0"
x-collection-name: Entertainment Express
x-complete: 1
info:
  title: Entertainment Express
  description: your-gateway-to-building-incredible-movie-tv-and-game-content-discovery-experiences-
  version: "2.0"
host: ee.iva-api.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Common/Companies/:
    get:
      summary: Paged list of companies.
      description: 'Companies are listed in a movie, show, or game response as those
        whom are involved with the program.  EX: Universal Pictures.'
      operationId: GetCompanies
      x-api-path-slug: commoncompanies-get
      parameters:
      - in: query
        name: Skip
        description: Offset for paging
      - in: query
        name: Take
        description: Maximum number of rows returned
      responses:
        200:
          description: OK
      tags:
      - Common
      - Companies
---
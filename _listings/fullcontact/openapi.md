---
swagger: "2.0"
x-collection-name: FullContact
x-complete: 1
info:
  title: FullContact Location API
  description: the-api-for-managing-fullcontact-locations
  termsOfService: https://www.fullcontact.com/terms/
  version: 1.0.0
host: api.fullcontact.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /company/lookup.json:
    get:
      summary: Get Company
      description: Get Company
      operationId: getCompany
      x-api-path-slug: companylookupjson-get
      parameters:
      - in: query
        name: apiKey
        description: This API key is assigned to you by FullContact
      - in: query
        name: callback
        description: If specified, the response will be wrapped as JSONP in a function
          call
      - in: query
        name: domain
        description: The domain of the company being looked up
      - in: query
        name: keyPeople
        description: ' If true, a list of Executive and VP level employees at this
          company will be returned under the keyPeople field'
      - in: query
        name: prettyPrint
        description: The prettyPrint parameter can be used to disable prettyprint
          formatting on the API response
      responses:
        200:
          description: OK
      tags:
      - Companies
---
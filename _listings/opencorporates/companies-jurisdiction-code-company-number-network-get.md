---
swagger: "2.0"
info:
  title: OpenCorporates Companies  Jurisdiction Code  Company Number Network
  description: nThis returns the immediate &#39;computed corporate network&#39; for
    the given company as a set of control relationships (i
  termsOfService: https://opencorporates.com/info/licence
  version: v.04
host: api.opencorporates.com
basePath: v0.4/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /companies/:jurisdiction_code/:company_number/network:
    get:
      summary: Companies  Jurisdiction Code  Company Number Network
      description: nThis returns the immediate &#39;computed corporate network&#39;
        for the given company as a set of control relationships (i
      operationId: companies--jurisdiction-code--company-number-network
      parameters:
      - in: query
        name: child_name
        description: the name of the child entity
      - in: query
        name: child_opencorporates_url
        description: the OpenCorporates URL of the child entity
      - in: query
        name: child_type
        description: the type of entity the child is
      - in: query
        name: confidence
        description: a computed confidence in the relationship based on the underlying
          statements
      - in: query
        name: parent_name
        description: the name of the parent entity
      - in: query
        name: parent_opencorporates_url
        description: the OpenCorporates URL of the parent entity
      - in: query
        name: parent_type
        description: the type of entity the parent is
      - in: query
        name: relationship_properties
        description: any additional properties of the relationship, e
      - in: query
        name: relationship_type
        description: the type of relationship, e
      responses:
        200:
          description: OK
      tags:
      - businesses
      - companies
      - :jurisdiction
      - code
      - :company
      - number
      - network
definitions: []
x-collection-name: OpenCorporates
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
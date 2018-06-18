---
swagger: "2.0"
x-collection-name: Apigee Edge
x-complete: 0
info:
  title: Apigee Edge Post Organizations Name Companies
  description: Creates a company in an organization.
  version: 1.0.0
host: api.enterprise.apigee.com
basePath: /v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /organizations/{org_name}/companies:
    get:
      summary: Get Organizations Name Companies
      description: Returns an expanded list of companies, displaying a full profile
        for each company in the organization.
      operationId: getOrganizationsOrgNameCompanies
      x-api-path-slug: organizationsorg-namecompanies-get
      parameters:
      - in: query
        name: expand
        description: Specify the Content Type
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
    post:
      summary: Post Organizations Name Companies
      description: Creates a company in an organization.
      operationId: postOrganizationsOrgNameCompanies
      x-api-path-slug: organizationsorg-namecompanies-post
      parameters:
      - in: query
        name: Content-Type
        description: Specify the Content Type
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
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
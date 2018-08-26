---
swagger: "2.0"
x-collection-name: LogMeIn
x-complete: 0
info:
  title: GoToAssist Remote Support Get Companies
  description: "This method retrieves information about the companies that the authenticated
    user has access to.\n\n                    \n  Query Parameters (all are optional)
    \                 \n    q      string      A search query to filter the returned
    records. Performs a contains check on companyName    \n    limit      integer
    \     The maximum number of records to be fetched. Default limit is 50. Valid
    range is 1 to 50. Greater than 50 results in bad request.    \n    offset      number
    \     Zero based offset for the first record to return. Default value is 0.    \n
    \   sortField      string      Name of the field to sort by, can be one of companyId,
    companyName.    \n    sortOrder            Sort order can be specified explicitly.
    Allowed values are \u201Casc\u201D for ascending order and \u201Cdesc\u201D for
    descending order.    \n\n\nStatus Codes              \n              \n    Staus
    Code      description    \n    200 OK      The information was successfully retrieved
    \   \n    401 Unauthorized      An authentication parameter was passed, but either
    it was invalid or the technician is not entitled with a Remote Support seat;    \n
    \   403 Forbidden      Access denied. User doesn\u2019t have required roles    \n
    \   404 Not Found      No companies found    \n    405 Method Not Allowed      The
    method was entered incorrectly (i.e., the technician tried to use POST, PUT etc.
    instead of GET)    \n    500 Internal Server Error      An unhandled error occurred"
  version: 1.0.0
host: api.getgo.com
basePath: /G2A/rest/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /companies:
    get:
      summary: Get Companies
      description: "This method retrieves information about the companies that the
        authenticated user has access to.\n\n                    \n  Query Parameters
        (all are optional)                  \n    q      string      A search query
        to filter the returned records. Performs a contains check on companyName    \n
        \   limit      integer      The maximum number of records to be fetched. Default
        limit is 50. Valid range is 1 to 50. Greater than 50 results in bad request.
        \   \n    offset      number      Zero based offset for the first record to
        return. Default value is 0.    \n    sortField      string      Name of the
        field to sort by, can be one of companyId, companyName.    \n    sortOrder
        \           Sort order can be specified explicitly. Allowed values are \u201Casc\u201D
        for ascending order and \u201Cdesc\u201D for descending order.    \n\n\nStatus
        Codes              \n              \n    Staus Code      description    \n
        \   200 OK      The information was successfully retrieved    \n    401 Unauthorized
        \     An authentication parameter was passed, but either it was invalid or
        the technician is not entitled with a Remote Support seat;    \n    403 Forbidden
        \     Access denied. User doesn\u2019t have required roles    \n    404 Not
        Found      No companies found    \n    405 Method Not Allowed      The method
        was entered incorrectly (i.e., the technician tried to use POST, PUT etc.
        instead of GET)    \n    500 Internal Server Error      An unhandled error
        occurred"
      operationId: CompaniesGet
      x-api-path-slug: companies-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
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
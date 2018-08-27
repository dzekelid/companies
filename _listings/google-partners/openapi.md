swagger: "2.0"
x-collection-name: Google Partners
x-complete: 1
info:
  title: Google Partners
  description: searches-certified-companies-and-creates-contact-leads-with-them-and-also-audits-the-usage-of-clients-
  contact:
    name: Google
    url: https://google.com
  version: v2
host: partners.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/companies:
    get:
      summary: Get Companies
      description: Lists companies.
      operationId: partners.companies.list
      x-api-path-slug: v2companies-get
      parameters:
      - in: query
        name: address
        description: The address to use when searching for companies
      - in: query
        name: companyName
        description: Company name to search for
      - in: query
        name: gpsMotivations
        description: List of reasons for using Google Partner Search to get companies
      - in: query
        name: industries
        description: List of industries the company can help with
      - in: query
        name: languageCodes
        description: List of language codes that company can support
      - in: query
        name: maxMonthlyBudget.currencyCode
        description: The 3-letter currency code defined in ISO 4217
      - in: query
        name: maxMonthlyBudget.nanos
        description: Number of nano (10^-9) units of the amount
      - in: query
        name: maxMonthlyBudget.units
        description: The whole units of the amount
      - in: query
        name: minMonthlyBudget.currencyCode
        description: The 3-letter currency code defined in ISO 4217
      - in: query
        name: minMonthlyBudget.nanos
        description: Number of nano (10^-9) units of the amount
      - in: query
        name: minMonthlyBudget.units
        description: The whole units of the amount
      - in: query
        name: orderBy
        description: How to order addresses within the returned companies
      - in: query
        name: pageSize
        description: Requested page size
      - in: query
        name: pageToken
        description: A token identifying a page of results that the server returns
      - in: query
        name: requestMetadata.experimentIds
        description: Experiment IDs the current request belongs to
      - in: query
        name: requestMetadata.locale
        description: Locale to use for the current request
      - in: query
        name: requestMetadata.partnersSessionId
        description: Google Partners session ID
      - in: query
        name: requestMetadata.trafficSource.trafficSourceId
        description: Identifier to indicate where the traffic comes from
      - in: query
        name: requestMetadata.trafficSource.trafficSubId
        description: Second level identifier to indicate where the traffic comes from
      - in: query
        name: requestMetadata.userOverrides.ipAddress
        description: IP address to use instead of the users geo-located IP address
      - in: query
        name: requestMetadata.userOverrides.userId
        description: Logged-in user ID to impersonate instead of the users ID
      - in: query
        name: services
        description: List of services that the returned agencies should provide
      - in: query
        name: specializations
        description: List of specializations that the returned agencies should provide
      - in: query
        name: view
        description: The view of the `Company` resource to be returned
      - in: query
        name: websiteUrl
        description: Website URL that will help to find a better matched company
      responses:
        200:
          description: OK
      tags:
      - Company
    patch:
      summary: Update Company
      description: |-
        Update company.
        Should only be called within the context of an authorized logged in user.
      operationId: partners.updateCompanies
      x-api-path-slug: v2companies-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: requestMetadata.experimentIds
        description: Experiment IDs the current request belongs to
      - in: query
        name: requestMetadata.locale
        description: Locale to use for the current request
      - in: query
        name: requestMetadata.partnersSessionId
        description: Google Partners session ID
      - in: query
        name: requestMetadata.trafficSource.trafficSourceId
        description: Identifier to indicate where the traffic comes from
      - in: query
        name: requestMetadata.trafficSource.trafficSubId
        description: Second level identifier to indicate where the traffic comes from
      - in: query
        name: requestMetadata.userOverrides.ipAddress
        description: IP address to use instead of the users geo-located IP address
      - in: query
        name: requestMetadata.userOverrides.userId
        description: Logged-in user ID to impersonate instead of the users ID
      - in: query
        name: updateMask
        description: Standard field mask for the set of fields to be updated
      responses:
        200:
          description: OK
      tags:
      - Company
  /v2/companies/{companyId}:
    get:
      summary: Get Company
      description: Gets a company.
      operationId: partners.companies.get
      x-api-path-slug: v2companiescompanyid-get
      parameters:
      - in: query
        name: address
        description: The address to use for sorting the companys addresses by proximity
      - in: path
        name: companyId
        description: The ID of the company to retrieve
      - in: query
        name: currencyCode
        description: If the companys budget is in a different currency code than this
          one, thenthe converted budget is converted to this currency code
      - in: query
        name: orderBy
        description: How to order addresses within the returned company
      - in: query
        name: requestMetadata.experimentIds
        description: Experiment IDs the current request belongs to
      - in: query
        name: requestMetadata.locale
        description: Locale to use for the current request
      - in: query
        name: requestMetadata.partnersSessionId
        description: Google Partners session ID
      - in: query
        name: requestMetadata.trafficSource.trafficSourceId
        description: Identifier to indicate where the traffic comes from
      - in: query
        name: requestMetadata.trafficSource.trafficSubId
        description: Second level identifier to indicate where the traffic comes from
      - in: query
        name: requestMetadata.userOverrides.ipAddress
        description: IP address to use instead of the users geo-located IP address
      - in: query
        name: requestMetadata.userOverrides.userId
        description: Logged-in user ID to impersonate instead of the users ID
      - in: query
        name: view
        description: The view of `Company` resource to be returned
      responses:
        200:
          description: OK
      tags:
      - Company
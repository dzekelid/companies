---
swagger: "2.0"
x-collection-name: Apigee
x-complete: 0
info:
  title: Apigee Edge Get Organizations Name Companies Company Name Appfamilies
  description: An expanded list of all app families in an organization, listing Apps
    in the collection.
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
  /organizations/{org_name}/companies/{company_name}:
    get:
      summary: Get Organizations Name Companies Company Name
      description: Gets details for a Company.
      operationId: getOrganizationsOrgNameCompaniesCompanyName
      x-api-path-slug: organizationsorg-namecompaniescompany-name-get
      parameters:
      - in: path
        name: company_name
        description: Mention the company name
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
    put:
      summary: Put Organizations Name Companies Company Name
      description: Updates an existing Company.
      operationId: putOrganizationsOrgNameCompaniesCompanyName
      x-api-path-slug: organizationsorg-namecompaniescompany-name-put
      parameters:
      - in: path
        name: company_name
        description: Mention the company name
      - in: query
        name: Content-Type
        description: Specify the content type
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
    delete:
      summary: Delete Organizations Name Companies Company Name
      description: Deletes an existing Company.
      operationId: deleteOrganizationsOrgNameCompaniesCompanyName
      x-api-path-slug: organizationsorg-namecompaniescompany-name-delete
      parameters:
      - in: path
        name: company_name
        description: Mention the company name
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
  /organizations/{org_name}/companies/{company_name}/developers:
    get:
      summary: Get Organizations Name Companies Company Name Developers
      description: Lists all developers associated with a company.
      operationId: getOrganizationsOrgNameCompaniesCompanyNameDevelopers
      x-api-path-slug: organizationsorg-namecompaniescompany-namedevelopers-get
      parameters:
      - in: path
        name: company_name
        description: Mention the company name
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
      - Developers
    post:
      summary: Post Organizations Name Companies Company Name Developers
      description: Adds a developer to a company.
      operationId: postOrganizationsOrgNameCompaniesCompanyNameDevelopers
      x-api-path-slug: organizationsorg-namecompaniescompany-namedevelopers-post
      parameters:
      - in: path
        name: company_name
        description: Mention the company name
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
      - Companies
      - Developers
  /organizations/{org_name}/companies/{company_name}/developers/{developer_email}:
    delete:
      summary: Delete Organizations Name Companies Company Name Developers Developer
        Email
      description: Removes the association of a Developer with a Company.
      operationId: deleteOrganizationsOrgNameCompaniesCompanyNameDevelopersDeveloperEmail
      x-api-path-slug: organizationsorg-namecompaniescompany-namedevelopersdeveloper-email-delete
      parameters:
      - in: path
        name: company_name
        description: Mention the company name
      - in: query
        name: Developer_email
        description: Mention the developer email
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
      - Developers
      - Developer
      - Email
  /organizations/{org_name}/companies/{company_name}/apps:
    get:
      summary: Get Organizations Name Companies Company Name Apps
      description: Gets an expanded list company apps .
      operationId: getOrganizationsOrgNameCompaniesCompanyNameApps
      x-api-path-slug: organizationsorg-namecompaniescompany-nameapps-get
      parameters:
      - in: path
        name: company_name
        description: Mention the company name
      - in: query
        name: expand
        description: Specify expand value as true
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
      - Applications
      - s
    post:
      summary: Post Organizations Name Companies Company Name Apps
      description: Creates an app for a company.
      operationId: postOrganizationsOrgNameCompaniesCompanyNameApps
      x-api-path-slug: organizationsorg-namecompaniescompany-nameapps-post
      parameters:
      - in: path
        name: company_name
        description: Mention the company name
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
      - Companies
      - Applications
      - s
  /organizations/{org_name}/companies/{company_name}/apps/{app_name}:
    get:
      summary: Get Organizations Name Companies Company Name Apps App Name
      description: Gets the count    of API resources for a company app.
      operationId: getOrganizationsOrgNameCompaniesCompanyNameAppsAppName
      x-api-path-slug: organizationsorg-namecompaniescompany-nameappsapp-name-get
      parameters:
      - in: path
        name: app_name
        description: Mention the app name
      - in: path
        name: company_name
        description: Mention the company name
      - in: query
        name: entity
        description: Mention entity as API resources
      - in: path
        name: org_name
        description: Mention the organization name
      - in: query
        name: query
        description: Specify query value as count
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
      - Applications
      - ""
    post:
      summary: Post Organizations Name Companies Company Name Apps App Name
      description: Updates an existing company app.
      operationId: postOrganizationsOrgNameCompaniesCompanyNameAppsAppName
      x-api-path-slug: organizationsorg-namecompaniescompany-nameappsapp-name-post
      parameters:
      - in: path
        name: app_name
        description: Mention the app name
      - in: path
        name: company_name
        description: Mention the company name
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
      - Companies
      - Applications
      - ""
    delete:
      summary: Delete Organizations Name Companies Company Name Apps App Name
      description: Deletes a company app.
      operationId: deleteOrganizationsOrgNameCompaniesCompanyNameAppsAppName
      x-api-path-slug: organizationsorg-namecompaniescompany-nameappsapp-name-delete
      parameters:
      - in: path
        name: app_name
        description: Mention the app name
      - in: path
        name: company_name
        description: Mention the company name
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
      - Applications
      - ""
  /organizations/{org_name}/companies/{company_name}/apps/{app_name}/keys/{consumer_key}:
    get:
      summary: Get Organizations Name Companies Company Name Apps App Name Keys Consumer
        Key
      description: Gets the consumer key issued to a company app.
      operationId: getOrganizationsOrgNameCompaniesCompanyNameAppsAppNameKeysConsumerKey
      x-api-path-slug: organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-get
      parameters:
      - in: path
        name: app_name
        description: Mention the app name
      - in: path
        name: company_name
        description: Mention the company name
      - in: path
        name: consumer_key
        description: Mention the consumer key
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
      - Applications
      - ""
      - Keys
      - Consumer
      - Key
    post:
      summary: Post Organizations Name Companies Company Name Apps App Name Keys Consumer
        Key
      description: Revokes the specific key of a company app.
      operationId: postOrganizationsOrgNameCompaniesCompanyNameAppsAppNameKeysConsumerKey
      x-api-path-slug: organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-post
      parameters:
      - in: query
        name: action
        description: Mention action as revoke
      - in: path
        name: app_name
        description: Mention the app name
      - in: path
        name: company_name
        description: Mention the company name
      - in: path
        name: consumer_key
        description: Mention the consumer key
      - in: query
        name: Content-Type
        description: Specify content type
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
      - Applications
      - ""
      - Keys
      - Consumer
      - Key
    delete:
      summary: Delete Organizations Name Companies Company Name Apps App Name Keys
        Consumer Key
      description: Deletes a company app key.
      operationId: deleteOrganizationsOrgNameCompaniesCompanyNameAppsAppNameKeysConsumerKey
      x-api-path-slug: organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-delete
      parameters:
      - in: path
        name: app_name
        description: Mention the app name
      - in: path
        name: company_name
        description: Mention the company name
      - in: path
        name: consumer_key
        description: Mention the consumer key
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
      - Applications
      - ""
      - Keys
      - Consumer
      - Key
  /organizations/{org_name}/companies/{company_name}/appfamilies:
    get:
      summary: Get Organizations Name Companies Company Name Appfamilies
      description: An expanded list of all app families in an organization, listing
        Apps in the collection.
      operationId: getOrganizationsOrgNameCompaniesCompanyNameAppfamilies
      x-api-path-slug: organizationsorg-namecompaniescompany-nameappfamilies-get
      parameters:
      - in: path
        name: company_name
        description: Mention the company name
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Companies
      - Companies
      - Applications
      - Families
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
---
name: Apigee
x-slug: apigee
description: Apigee Edge is a platform for developing and managing API proxies. Think
  of a proxy as an abstraction layer that fronts for your backend service APIs and
  provides value-added features like security, rate limiting, quotas, analytics, and
  more. The primary consumers of Edge API proxies are app developers who want to use
  your backend services.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Companies
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/apis.md
specificationVersion: "0.14"
apis:
- name: Apigee Edge Get Organizations Name Companies
  x-api-slug: apigee-edge
  description: Returns an expanded list of companies, displaying a full profile for
    each company in the organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies
  tags: Organizations,Companies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompanies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompanies-get-openapi.md
- name: Apigee Edge Post Organizations Name Companies
  x-api-slug: apigee-edge
  description: Creates a company in an organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies
  tags: Organizations,Companies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompanies-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompanies-post-openapi.md
- name: Apigee Edge Get Organizations Name Companies Company Name
  x-api-slug: apigee-edge
  description: Gets details for a Company.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}
  tags: Organizations,Companies,Companies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-name-get-openapi.md
- name: Apigee Edge Put Organizations Name Companies Company Name
  x-api-slug: apigee-edge
  description: Updates an existing Company.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}
  tags: Organizations,Companies,Companies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-name-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-name-put-openapi.md
- name: Apigee Edge Delete Organizations Name Companies Company Name
  x-api-slug: apigee-edge
  description: Deletes an existing Company.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}
  tags: Organizations,Companies,Companies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-name-delete-openapi.md
- name: Apigee Edge Get Organizations Name Companies Company Name Developers
  x-api-slug: apigee-edge
  description: Lists all developers associated with a company.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/developers
  tags: Organizations,Companies,Companies,Developers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-namedevelopers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-namedevelopers-get-openapi.md
- name: Apigee Edge Post Organizations Name Companies Company Name Developers
  x-api-slug: apigee-edge
  description: Adds a developer to a company.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/developers
  tags: Organizations,Companies,Companies,Developers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-namedevelopers-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-namedevelopers-post-openapi.md
- name: Apigee Edge Delete Organizations Name Companies Company Name Developers Developer
    Email
  x-api-slug: apigee-edge
  description: Removes the association of a Developer with a Company.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/developers/{developer_email}
  tags: Organizations,Companies,Companies,Developers,Developer,Email
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-namedevelopersdeveloper-email-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-namedevelopersdeveloper-email-delete-openapi.md
- name: Apigee Edge Get Organizations Name Companies Company Name Apps
  x-api-slug: apigee-edge
  description: Gets an expanded list company apps .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps
  tags: Organizations,Companies,Companies,Applications,s
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameapps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameapps-get-openapi.md
- name: Apigee Edge Post Organizations Name Companies Company Name Apps
  x-api-slug: apigee-edge
  description: Creates an app for a company.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps
  tags: Organizations,Companies,Companies,Applications,s
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameapps-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameapps-post-openapi.md
- name: Apigee Edge Get Organizations Name Companies Company Name Apps App Name
  x-api-slug: apigee-edge
  description: Gets the count    of API resources for a company app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps/{app_name}
  tags: Organizations,Companies,Companies,Applications,
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappsapp-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappsapp-name-get-openapi.md
- name: Apigee Edge Post Organizations Name Companies Company Name Apps App Name
  x-api-slug: apigee-edge
  description: Updates an existing company app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps/{app_name}
  tags: Organizations,Companies,Companies,Applications,
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappsapp-name-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappsapp-name-post-openapi.md
- name: Apigee Edge Delete Organizations Name Companies Company Name Apps App Name
  x-api-slug: apigee-edge
  description: Deletes a company app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps/{app_name}
  tags: Organizations,Companies,Companies,Applications,
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappsapp-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappsapp-name-delete-openapi.md
- name: Apigee Edge Get Organizations Name Companies Company Name Apps App Name Keys
    Consumer Key
  x-api-slug: apigee-edge
  description: Gets the consumer key issued to a company app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps/{app_name}/keys/{consumer_key}
  tags: Organizations,Companies,Companies,Applications,,Keys,Consumer,Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-get-openapi.md
- name: Apigee Edge Post Organizations Name Companies Company Name Apps App Name Keys
    Consumer Key
  x-api-slug: apigee-edge
  description: Revokes the specific key of a company app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps/{app_name}/keys/{consumer_key}
  tags: Organizations,Companies,Companies,Applications,,Keys,Consumer,Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-post-openapi.md
- name: Apigee Edge Delete Organizations Name Companies Company Name Apps App Name
    Keys Consumer Key
  x-api-slug: apigee-edge
  description: Deletes a company app key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps/{app_name}/keys/{consumer_key}
  tags: Organizations,Companies,Companies,Applications,,Keys,Consumer,Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-delete-openapi.md
- name: Apigee Edge Get Organizations Name Companies Company Name Appfamilies
  x-api-slug: apigee-edge
  description: An expanded list of all app families in an organization, listing Apps
    in the collection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/appfamilies
  tags: Organizations,Companies,Companies,Applications,Families
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamilies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamilies-get-openapi.md
- name: Apigee Edge Post Organizations Name Companies Company Name Appfamilies
  x-api-slug: apigee-edge
  description: Creates an app family.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/appfamilies
  tags: Organizations,Companies,Companies,Applications,Families
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamilies-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamilies-post-openapi.md
- name: Apigee Edge Get Organizations Name Companies Company Name Appfamilies Appfamily
    Name
  x-api-slug: apigee-edge
  description: Gets a list of apps in an appfamily.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/appfamilies/{appfamily_name}
  tags: Organizations,Companies,Companies,Applications,Families,Applications,family
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-get-openapi.md
- name: Apigee Edge Post Organizations Name Companies Company Name Appfamilies Appfamily
    Name
  x-api-slug: apigee-edge
  description: Updates an existing app family.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/appfamilies/{appfamily_name}
  tags: Organizations,Companies,Companies,Applications,Families,Applications,family
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-post-openapi.md
- name: Apigee Edge Delete Organizations Name Companies Company Name Appfamilies Appfamily
    Name
  x-api-slug: apigee-edge
  description: Deletes an App Family and all Apps it contains.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/appfamilies/{appfamily_name}
  tags: Organizations,Companies,Companies,Applications,Families,Applications,family
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-name-delete-openapi.md
- name: Apigee Edge Delete Organizations Name Companies Company Name Appfamilies Appfamily
    Name Apps App Name
  x-api-slug: apigee-edge
  description: Removes an App from an App Family.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/appfamilies/{appfamily_name}/apps/{app_name}
  tags: Organizations,Companies,Companies,Applications,Families,Applications,family,Applications,
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-nameappsapp-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappfamiliesappfamily-nameappsapp-name-delete-openapi.md
- name: Apigee Edge
  x-api-slug: apigee-edge
  description: Apigee Edge is a platform for developing and managing API proxies.
    Think of a proxy as an abstraction layer that fronts for your backend service
    APIs and provides value-added features like security, rate limiting, quotas, analytics,
    and more. The primary consumers of Edge API proxies are app developers who want
    to use your backend services.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1/
  tags: Companies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/apigee/openapi.md
x-common:
- type: x-website
  url: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
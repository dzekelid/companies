---
name: Intrinio
x-slug: intrinio
description: Market for financial data APIs and analytics applications built with
  those data feeds. Affordable, easy to access financial data for developers and investors
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IntrinioLogo-Green-optimized.png
x-kinRank: "8"
x-alexaRank: "321628"
tags: Companies
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/intrinio/apis.md
specificationVersion: "0.14"
apis:
- name: Intrinio API Company Master
  x-api-slug: intrinio-api
  description: Returns the master list of all companies covered by the Intrinio Data
    Marketplace.  You can view the Company/Security Master here.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IntrinioLogo-Green-optimized.png
  humanURL: https://intrinio.com
  baseURL: https://api.intrinio.com////companies
  tags: Market Data,Companies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/intrinio/companies-get-openapi.md
- name: Intrinio API Company SEC Filings
  x-api-slug: intrinio-api
  description: Returns the complete list of SEC filings for a company.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IntrinioLogo-Green-optimized.png
  humanURL: https://intrinio.com
  baseURL: https://api.intrinio.com////companies/filings
  tags: Market Data,Companies,Company Filings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/intrinio/companiesfilings-get-openapi.md
- name: Intrinio API Bank Holding Companies
  x-api-slug: intrinio-api
  description: Returns bank holding company list and information for all bank holding
    companies covered by Intrinio.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IntrinioLogo-Green-optimized.png
  humanURL: https://intrinio.com
  baseURL: https://api.intrinio.com////banks/holding_companies
  tags: Market Data,Holding Companies,Banks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/intrinio/banksholding-companies-get-openapi.md
- name: Intrinio API Company Executive Contacts
  x-api-slug: intrinio-api
  description: Returns a list of all information for an executive and their related
    companies.  Information includes the unique Intrinio executive company identifier,
    and detailed contact information for the executive at a specified company.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IntrinioLogo-Green-optimized.png
  humanURL: https://intrinio.com
  baseURL: https://api.intrinio.com////executives/companies
  tags: Market Data,Executives,companies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/intrinio/executivescompanies-get-openapi.md
- name: Intrinio API
  x-api-slug: intrinio-api
  description: Market for financial data APIs and analytics applications built with
    those data feeds. Affordable, easy to access financial data for developers and
    investors
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/IntrinioLogo-Green-optimized.png
  humanURL: https://intrinio.com
  baseURL: https://api.intrinio.com//
  tags: Companies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/intrinio/openapi.md
x-common:
- type: x-applications-showcase
  url: https://intrinio.com/marketplace/apps
- type: x-authentication
  url: http://docs.intrinio.com/#authentication
- type: x-blog
  url: http://blog.intrinio.com/
- type: x-blog-rss
  url: http://blog.intrinio.com/feed/
- type: x-code
  url: http://docs.intrinio.com/#sdks
- type: x-crunchbase
  url: https://crunchbase.com/organization/tribunat
- type: x-developer
  url: https://intrinio.com/we-love-developers
- type: x-documentation
  url: https://intrinio.com/marketplace/data
- type: x-email
  url: cfarley@intrinio.com
- type: x-email
  url: admin@intrinio.com
- type: x-email
  url: support@intrinio.com
- type: x-login
  url: https://intrinio.com/login
- type: x-partners
  url: https://intrinio.com/partners
- type: x-press
  url: https://intrinio.com/press
- type: x-rate-limits
  url: http://docs.intrinio.com/#limits
- type: x-selfservice-registration
  url: https://intrinio.com/signup
- type: x-spreadsheets
  url: http://docs.intrinio.com/#spreadsheet-add-ins
- type: x-support
  url: https://intrinio.com/help
- type: x-tutorial
  url: https://intrinio.com/tutorial/web_api
- type: x-twitter
  url: https://twitter.com/intrinio
- type: x-website
  url: https://intrinio.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
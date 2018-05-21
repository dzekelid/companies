---
swagger: "2.0"
x-collection-name: Intrinio
x-complete: 1
info:
  title: Intrinio
  description: through-our-intrinio-data-marketplace-we-offer-a-wide-selection-of-financial-data-feeds-sourced-by-our-own-proprietary-processes-as-well-as-from-many-data-vendors-the-primary-application-of-the-intrinio-api-is-for-use-in-thirdparty-applications-and-integrations-or-for-endusers-utilizing-the-excel-addin-and-google-sheets-addon-the-intrinio-api-uses-https-verbs-and-a-restful-endpoint-structure-which-makes-it-easy-to-request-data-from-intrinio-basic-authentication-is-administered-over-https-responses-are-delivered-in-json-format
  version: 1.0.0
host: api.intrinio.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /companies:
    get:
      summary: Company Master
      description: Returns the master list of all companies covered by the Intrinio
        Data Marketplace.  You can view the Company/Security Master here.
      operationId: company-master
      x-api-path-slug: companies-get
      parameters:
      - in: query
        name: latest_filing_date
        description: ' a date value that returns the list of companies whose latest
          SEC filing was filed on or after this date: YYYY'
        type: string
      - in: query
        name: page_number
        description: ' an integer greater than or equal to 1 for specifying the page
          number for the return values'
        type: string
      - in: query
        name: page_size
        description: ' an integer greater than 1 for specifying the number of results
          on each page'
        type: string
      - in: query
        name: query
        description: ' a string query search of company name or ticker symbol with
          the returned results being the relevant companies in compacted list format'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Companies
  /companies/filings:
    get:
      summary: Company SEC Filings
      description: Returns the complete list of SEC filings for a company.
      operationId: company-sec-filings
      x-api-path-slug: companiesfilings-get
      parameters:
      - in: query
        name: end_date
        description: ' the last filing date for which to return filings, in the format:
          YYYY'
        type: string
      - in: query
        name: identifier
        description: ' the stock market ticker symbol associated with the company&rsquo;s
          common stock'
        type: string
      - in: query
        name: page_number
        description: ' an integer greater than or equal to 1 for specifying the page
          number for the return values'
        type: string
      - in: query
        name: page_size
        description: ' an integer greater than 1 for specifying the number of results
          on each page'
        type: string
      - in: query
        name: report_type
        description: ' the report type of the filing requested: 10'
        type: string
      - in: query
        name: start_date
        description: ' the earliest filing date for which to return filings, in the
          format: YYYY'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Companies
      - Company Filings
  /banks/holding_companies:
    get:
      summary: Bank Holding Companies
      description: Returns bank holding company list and information for all bank
        holding companies covered by Intrinio.
      operationId: bank-holding-companies
      x-api-path-slug: banksholding-companies-get
      parameters:
      - in: query
        name: page_number
        description: ' an integer greater than or equal to 1 for specifying the page
          number for the return values'
        type: string
      - in: query
        name: page_size
        description: ' an integer greater than 1 for specifying the number of results
          on each page'
        type: string
      - in: query
        name: query
        description: ' used to search for a ticker or bank name to return relevant
          banks'
        type: string
      - in: query
        name: rssd_id
        description: ' the bank/bank holding company RSSD ID issued by the Federal
          Reserve: RSSD ID LOOKUP'
        type: string
      - in: query
        name: ticker
        description: ' the stock market ticker symbol associated with the companies
          common stock securities: '
        type: string
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Holding Companies
      - Banks
  /executives/companies:
    get:
      summary: Company Executive Contacts
      description: Returns a list of all information for an executive and their related
        companies.  Information includes the unique Intrinio executive company identifier,
        and detailed contact information for the executive at a specified company.
      operationId: company-executive-contacts
      x-api-path-slug: executivescompanies-get
      parameters:
      - in: query
        name: company
        description: ' the identifier for the specified security or company: '
        type: string
      - in: query
        name: identifier
        description: ' the Intrinio executive identifier'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Executives
      - companies
---
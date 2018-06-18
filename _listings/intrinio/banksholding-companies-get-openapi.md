---
swagger: "2.0"
x-collection-name: Intrinio
x-complete: 0
info:
  title: Intrinio API Bank Holding Companies
  description: Returns bank holding company list and information for all bank holding
    companies covered by Intrinio.
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
        description: 'a date value that returns the list of companies whose latest
          SEC filing was filed on or after this date: YYYY'
        type: string
      - in: query
        name: page_number
        description: an integer greater than or equal to 1 for specifying the page
          number for the return values
        type: string
      - in: query
        name: page_size
        description: an integer greater than 1 for specifying the number of results
          on each page
        type: string
      - in: query
        name: query
        description: a string query search of company name or ticker symbol with the
          returned results being the relevant companies in compacted list format
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
        description: 'the last filing date for which to return filings, in the format:
          YYYY'
        type: string
      - in: query
        name: identifier
        description: the stock market ticker symbol associated with the company&rsquo;s
          common stock
        type: string
      - in: query
        name: page_number
        description: an integer greater than or equal to 1 for specifying the page
          number for the return values
        type: string
      - in: query
        name: page_size
        description: an integer greater than 1 for specifying the number of results
          on each page
        type: string
      - in: query
        name: report_type
        description: 'the report type of the filing requested: 10'
        type: string
      - in: query
        name: start_date
        description: 'the earliest filing date for which to return filings, in the
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
        description: an integer greater than or equal to 1 for specifying the page
          number for the return values
        type: string
      - in: query
        name: page_size
        description: an integer greater than 1 for specifying the number of results
          on each page
        type: string
      - in: query
        name: query
        description: used to search for a ticker or bank name to return relevant banks
        type: string
      - in: query
        name: rssd_id
        description: 'the bank/bank holding company RSSD ID issued by the Federal
          Reserve: RSSD ID LOOKUP'
        type: string
      - in: query
        name: ticker
        description: 'the stock market ticker symbol associated with the companies
          common stock securities:'
        type: string
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Holding Companies
      - Banks
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
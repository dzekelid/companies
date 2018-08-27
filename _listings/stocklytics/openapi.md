swagger: "2.0"
x-collection-name: Stocklytics
x-complete: 1
info:
  title: Stocklytics Intraday Historical Stock Prices API
  description: the-intraday-historical-prices-api-allows-you-to-get-a-list-of-the-price-for-a-particular-stock-for-the-current-day-or-the-latest-day-of-trading-if-markets-are-closed-in-5-minute-intervals--this-data-is-perfect-for-generating-intraday-stock-graphs-or-performing-stock-analysis-in-near-realtime--data-for-this-api-is-updated-every-5-minutes-
  version: v1
host: api.stocklytics.com
basePath: /services/pressroom/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  companyData/{API_VERSION}/:
    get:
      summary: Company Data
      description: The Company Data API allows you to retrieve company information
        about a particular stock/ticker code.
      operationId: getCompanyData
      x-api-path-slug: companydataapi-version-get
      parameters:
      - in: query
        name: api_key
        description: Allows us to identify the request initiator
      - in: path
        name: API_VERSION
        description: Version of the API
      - in: query
        name: stock
        description: The stock code/ticker for the stock to look up
      responses:
        200:
          description: OK
      tags:
      - Companies
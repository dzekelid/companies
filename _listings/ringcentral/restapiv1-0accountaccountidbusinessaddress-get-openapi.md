---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 0
info:
  title: RingCentral Get Company Business Address
  description: "Returns business address of a company.\nApp Permission\nReadAccounts\nUser
    Permission\nReadCompanyInfo\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin to extension
    required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  version: 1.0.0
host: platform.ringcentral.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /restapi/v1.0/glip/companies/{companyId}:
    get:
      summary: Get Company Info
      description: |-
        Returns a company by ID.
        App Permission
        Glip
        User Permission
        Glip
        Usage Plan Group
        Light
      operationId: loadGlipCompany
      x-api-path-slug: restapiv1-0glipcompaniescompanyid-get
      parameters:
      - in: path
        name: companyId
        description: Internal identifier of an RC account/Glip company, or tilde (~)
          to indicate a company the current user belongs to
      responses:
        200:
          description: OK
      tags:
      - Company
      - Info
  /restapi/v1.0/account/{accountId}/business-hours:
    get:
      summary: Get Company Business Hours
      description: |-
        Returns company hours when answering rules are to be applied.
        App Permission
        ReadAccounts
        User Permission
        ReadUserAnsweringRules
        Usage Plan Group
        Light
      operationId: loadBusinesshoursInfo
      x-api-path-slug: restapiv1-0accountaccountidbusinesshours-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      responses:
        200:
          description: OK
      tags:
      - Company
      - Business
      - Hours
    put:
      summary: Update Company Business Hours
      description: "Updates company hours when answering rules are to be applied.\nApp
        Permission\nEditExtensions\nUser Permission\nEditUserAnsweringRules\nUsage
        Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n400\nAWR-176\nAt least one time range for [monday] required\n\n\n400\nAWR-177\nTime
        ranges limit for [monday] exceeded\n\n\n400\nCMN-101\nParameter [schedule.weeklyRanges]
        value is invalid"
      operationId: updateCompanyBusinessHours
      x-api-path-slug: restapiv1-0accountaccountidbusinesshours-put
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: body
        name: body
        description: JSON body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Company
      - Business
      - Hours
  /restapi/v1.0/account/{accountId}/answering-rule:
    post:
      summary: Create Company Call Handling Rule
      description: "Creates a company answering rule for a particular caller ID.\nApp
        Permission\nEditAccounts\nUser Permission\nEditCompanyAnsweringRules\nUsage
        Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n400\nAWR-106\nGreeting [Company] is duplicated\n\n\n400\nAWR-108\nOnly
        custom rule can be created\n\n\n400\nAWR-120\nBusiness Hours/After Hours schedule
        condition is allowed only with other answering rule conditions\n\n\n400\nAWR-121\nBusiness
        Hours not specified for current user\n\n\n400\nAWR-170\nInvalid greeting type:
        preset with [CompanyGreeting] must be used\n\n\n400\nAWR-172\n[extension]
        must be specified for [Bypass] call handling action\n\n\n400\nAWR-173\n[extension]
        can be specified for [Bypass] call handling action only\n\n\n400\nAWR-179\n[name]
        is too long: up to 127 symbols supported\n\n\n400\nAWR-182\nOnly bypass action
        is available in multi-level IVR mode\n\n\n400\nCMN-101\nParameter [callHandlingAction]
        value is invalid"
      operationId: createCompanyAnsweringRuleInfo
      x-api-path-slug: restapiv1-0accountaccountidansweringrule-post
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: body
        name: body
        description: JSON body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Company
      - Call
      - Handling
      - Rule
    get:
      summary: Get Company Call Handling Rules
      description: |-
        Returns a list of company answering rules.
        App Permission
        ReadAccounts
        User Permission
        ReadCompanyAnsweringRules
        Usage Plan Group
        Medium
      operationId: listCompanyAnsweringRule
      x-api-path-slug: restapiv1-0accountaccountidansweringrule-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      responses:
        200:
          description: OK
      tags:
      - Company
      - Call
      - Handling
      - Rules
  /restapi/v1.0/account/{accountId}/answering-rule/{ruleId}:
    get:
      summary: Get Company Call Handling Rule
      description: |-
        Returns a company answering rule by ID.
        App Permission
        ReadAccounts
        User Permission
        ReadCompanyAnsweringRules
        Usage Plan Group
        Light
      operationId: loadCompanyAnsweringRuleInfo
      x-api-path-slug: restapiv1-0accountaccountidansweringruleruleid-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: ruleId
        description: Internal identifier of an answering rule
      responses:
        200:
          description: OK
      tags:
      - Company
      - Call
      - Handling
      - Rule
    put:
      summary: Update Company Call Handling Rule
      description: "Updates a company answering rule.\nApp Permission\nEditAccounts\nUser
        Permission\nEditCompanyAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
        \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-164\nRule
        type cannot be changed\n\n\n400\nAWR-170\nInvalid greeting type: preset with
        [CompanyGreeting] must be used\n\n\n400\nAWR-172\n[extension] must be specified
        for [Bypass] call handling action\n\n\n400\nAWR-173\n[extension] can be specified
        for [Bypass] call handling action only\n\n\n400\nAWR-179\n[name] is too long:
        up to 127 symbols supported\n\n\n400\nAWR-182\nOnly bypass action is available
        in multi-level IVR mode\n\n\n400\nCMN-101\nParameter [callHandlingAction]
        value is invalid"
      operationId: updateCompanyAnsweringRuleInfo
      x-api-path-slug: restapiv1-0accountaccountidansweringruleruleid-put
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: body
        name: body
        description: JSON body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: ruleId
        description: Internal identifier of an answering rule
      responses:
        200:
          description: OK
      tags:
      - Company
      - Call
      - Handling
      - Rule
  /restapi/v1.0/account/{accountId}/greeting:
    post:
      summary: Create Custom Company Greeting
      description: "Creates a custom company greeting.\nApp Permission\nEditAccounts\nUser
        Permission\nReadUserInfo\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n
        \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-129\nInvalid
        attachment media type\n\n\n400\nAWR-178\nGreeting type [Voicemail] is not
        applicable to company rule\n\n\n400\nCMN-101\nParameter [type] value is invalid\n\n\n400\nCMN-102\nResource
        for parameter [answeringRule.id] is not found"
      operationId: getCompanyGreeting
      x-api-path-slug: restapiv1-0accountaccountidgreeting-post
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: body
        name: body
        description: JSON body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Custom
      - Company
      - Greeting
  /restapi/v1.0/account/{accountId}:
    get:
      summary: Get Company Info
      description: "Returns basic information about a particular RingCentral customer
        account.\nApp Permission\nReadAccounts\nUser Permission\nReadCompanyInfo\nUsage
        Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
        method not supported\n\n\n401\nOAU-213\nToken not found\n\n\n403\nCMN-401\nIn
        order to call this API endpoint, application needs to have [ReadAccounts]
        permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
      operationId: loadAccount
      x-api-path-slug: restapiv1-0accountaccountid-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      responses:
        200:
          description: OK
      tags:
      - Company
      - Info
  /restapi/v1.0/account/{accountId}/business-address:
    get:
      summary: Get Company Business Address
      description: "Returns business address of a company.\nApp Permission\nReadAccounts\nUser
        Permission\nReadCompanyInfo\nUsage Plan Group\nLight\nError Codes\n\n \n  \n
        \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin
        to extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
        order to call this API endpoint, application needs to have [ReadAccounts]
        permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
      operationId: loadAccountBusinessAddress
      x-api-path-slug: restapiv1-0accountaccountidbusinessaddress-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      responses:
        200:
          description: OK
      tags:
      - Company
      - Business
      - Ress
  /restapi/v1.0/account/{accountId}/phone-number:
    get:
      summary: Get All Company Phone Numbers
      description: "Returns the list of phone numbers assigned to RingCentral customer
        account. Both company-level and extension-level numbers are returned.\nApp
        Permission\nReadAccounts\nUser Permission\nReadCompanyPhoneNumbers\nUsage
        Plan Group\nHeavy\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n400\nCMN-101\nParameter [perPage] value is invalid\n\n\n401\nCMN-405\nLogin
        to extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
        order to call this API endpoint, application needs to have [ReadAccounts]
        permission\n\n\n404\nCMN-102\nResource for parameter [accountId] is not found"
      operationId: listAccountPhoneNumbers
      x-api-path-slug: restapiv1-0accountaccountidphonenumber-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: query
        name: page
        description: Indicates the page number to retrieve
      - in: query
        name: perPage
        description: Indicates the page size (number of items)
      - in: query
        name: usageType
        description: Usage type of a phone number
      responses:
        200:
          description: OK
      tags:
      - Company
      - Phone
      - Numbers
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
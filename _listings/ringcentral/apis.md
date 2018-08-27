---
name: RingCentral
x-slug: ringcentral
description: 'RingCentral, Inc. (NYSE: RNG) is a global provider of cloud enterprise
  unified communications and collaboration solutions. More flexible and cost-effective
  than legacy on-premise systems, RingCentral empowers today&rsquo;s mobile and distributed
  workforces to be connected anywhere and on any device through voice, video, team
  messaging, collaboration, SMS, conferencing, online meetings, contact center, and
  fax. RingCentral provides an open platform that integrates with today&rsquo;s leading
  business apps while giving customers the flexibility to customize their own workflows.'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
x-kinRank: "7"
x-alexaRank: "7180"
tags: Companies
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/apis.md
specificationVersion: "0.14"
apis:
- name: RingCentral Connect Platform API Explorer - Get Company Info
  x-api-slug: restapiv1-0glipcompaniescompanyid-get
  description: |-
    Returns a company by ID.
    App Permission
    Glip
    User Permission
    Glip
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0glipcompaniescompanyid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0glipcompaniescompanyid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Business Hours
  x-api-slug: restapiv1-0accountaccountidbusinesshours-get
  description: |-
    Returns company hours when answering rules are to be applied.
    App Permission
    ReadAccounts
    User Permission
    ReadUserAnsweringRules
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidbusinesshours-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Company Business Hours
  x-api-slug: restapiv1-0accountaccountidbusinesshours-put
  description: "Updates company hours when answering rules are to be applied.\nApp
    Permission\nEditExtensions\nUser Permission\nEditUserAnsweringRules\nUsage Plan
    Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n400\nAWR-176\nAt least one time range for [monday] required\n\n\n400\nAWR-177\nTime
    ranges limit for [monday] exceeded\n\n\n400\nCMN-101\nParameter [schedule.weeklyRanges]
    value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidbusinesshours-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringrule-post
  description: "Creates a company answering rule for a particular caller ID.\nApp
    Permission\nEditAccounts\nUser Permission\nEditCompanyAnsweringRules\nUsage Plan
    Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n400\nAWR-106\nGreeting [Company] is duplicated\n\n\n400\nAWR-108\nOnly
    custom rule can be created\n\n\n400\nAWR-120\nBusiness Hours/After Hours schedule
    condition is allowed only with other answering rule conditions\n\n\n400\nAWR-121\nBusiness
    Hours not specified for current user\n\n\n400\nAWR-170\nInvalid greeting type:
    preset with [CompanyGreeting] must be used\n\n\n400\nAWR-172\n[extension] must
    be specified for [Bypass] call handling action\n\n\n400\nAWR-173\n[extension]
    can be specified for [Bypass] call handling action only\n\n\n400\nAWR-179\n[name]
    is too long: up to 127 symbols supported\n\n\n400\nAWR-182\nOnly bypass action
    is available in multi-level IVR mode\n\n\n400\nCMN-101\nParameter [callHandlingAction]
    value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidansweringrule-get
  description: |-
    Returns a list of company answering rules.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-get
  description: |-
    Returns a company answering rule by ID.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-put
  description: "Updates a company answering rule.\nApp Permission\nEditAccounts\nUser
    Permission\nEditCompanyAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-164\nRule
    type cannot be changed\n\n\n400\nAWR-170\nInvalid greeting type: preset with [CompanyGreeting]
    must be used\n\n\n400\nAWR-172\n[extension] must be specified for [Bypass] call
    handling action\n\n\n400\nAWR-173\n[extension] can be specified for [Bypass] call
    handling action only\n\n\n400\nAWR-179\n[name] is too long: up to 127 symbols
    supported\n\n\n400\nAWR-182\nOnly bypass action is available in multi-level IVR
    mode\n\n\n400\nCMN-101\nParameter [callHandlingAction] value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Custom Company Greeting
  x-api-slug: restapiv1-0accountaccountidgreeting-post
  description: "Creates a custom company greeting.\nApp Permission\nEditAccounts\nUser
    Permission\nReadUserInfo\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-129\nInvalid attachment
    media type\n\n\n400\nAWR-178\nGreeting type [Voicemail] is not applicable to company
    rule\n\n\n400\nCMN-101\nParameter [type] value is invalid\n\n\n400\nCMN-102\nResource
    for parameter [answeringRule.id] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidgreeting-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Info
  x-api-slug: restapiv1-0accountaccountid-get
  description: "Returns basic information about a particular RingCentral customer
    account.\nApp Permission\nReadAccounts\nUser Permission\nReadCompanyInfo\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n401\nOAU-213\nToken not found\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Business Address
  x-api-slug: restapiv1-0accountaccountidbusinessaddress-get
  description: "Returns business address of a company.\nApp Permission\nReadAccounts\nUser
    Permission\nReadCompanyInfo\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin to extension
    required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidbusinessaddress-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get All Company Phone Numbers
  x-api-slug: restapiv1-0accountaccountidphonenumber-get
  description: "Returns the list of phone numbers assigned to RingCentral customer
    account. Both company-level and extension-level numbers are returned.\nApp Permission\nReadAccounts\nUser
    Permission\nReadCompanyPhoneNumbers\nUsage Plan Group\nHeavy\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [perPage] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource for parameter
    [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidphonenumber-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Info
  x-api-slug: restapiv1-0glipcompaniescompanyid-get
  description: |-
    Returns a company by ID.
    App Permission
    Glip
    User Permission
    Glip
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0glipcompaniescompanyid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0glipcompaniescompanyid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Business Hours
  x-api-slug: restapiv1-0accountaccountidbusinesshours-get
  description: |-
    Returns company hours when answering rules are to be applied.
    App Permission
    ReadAccounts
    User Permission
    ReadUserAnsweringRules
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidbusinesshours-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Company Business Hours
  x-api-slug: restapiv1-0accountaccountidbusinesshours-put
  description: "Updates company hours when answering rules are to be applied.\nApp
    Permission\nEditExtensions\nUser Permission\nEditUserAnsweringRules\nUsage Plan
    Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n400\nAWR-176\nAt least one time range for [monday] required\n\n\n400\nAWR-177\nTime
    ranges limit for [monday] exceeded\n\n\n400\nCMN-101\nParameter [schedule.weeklyRanges]
    value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidbusinesshours-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringrule-post
  description: "Creates a company answering rule for a particular caller ID.\nApp
    Permission\nEditAccounts\nUser Permission\nEditCompanyAnsweringRules\nUsage Plan
    Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n400\nAWR-106\nGreeting [Company] is duplicated\n\n\n400\nAWR-108\nOnly
    custom rule can be created\n\n\n400\nAWR-120\nBusiness Hours/After Hours schedule
    condition is allowed only with other answering rule conditions\n\n\n400\nAWR-121\nBusiness
    Hours not specified for current user\n\n\n400\nAWR-170\nInvalid greeting type:
    preset with [CompanyGreeting] must be used\n\n\n400\nAWR-172\n[extension] must
    be specified for [Bypass] call handling action\n\n\n400\nAWR-173\n[extension]
    can be specified for [Bypass] call handling action only\n\n\n400\nAWR-179\n[name]
    is too long: up to 127 symbols supported\n\n\n400\nAWR-182\nOnly bypass action
    is available in multi-level IVR mode\n\n\n400\nCMN-101\nParameter [callHandlingAction]
    value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidansweringrule-get
  description: |-
    Returns a list of company answering rules.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-get
  description: |-
    Returns a company answering rule by ID.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-put
  description: "Updates a company answering rule.\nApp Permission\nEditAccounts\nUser
    Permission\nEditCompanyAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-164\nRule
    type cannot be changed\n\n\n400\nAWR-170\nInvalid greeting type: preset with [CompanyGreeting]
    must be used\n\n\n400\nAWR-172\n[extension] must be specified for [Bypass] call
    handling action\n\n\n400\nAWR-173\n[extension] can be specified for [Bypass] call
    handling action only\n\n\n400\nAWR-179\n[name] is too long: up to 127 symbols
    supported\n\n\n400\nAWR-182\nOnly bypass action is available in multi-level IVR
    mode\n\n\n400\nCMN-101\nParameter [callHandlingAction] value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Custom Company Greeting
  x-api-slug: restapiv1-0accountaccountidgreeting-post
  description: "Creates a custom company greeting.\nApp Permission\nEditAccounts\nUser
    Permission\nReadUserInfo\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-129\nInvalid attachment
    media type\n\n\n400\nAWR-178\nGreeting type [Voicemail] is not applicable to company
    rule\n\n\n400\nCMN-101\nParameter [type] value is invalid\n\n\n400\nCMN-102\nResource
    for parameter [answeringRule.id] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidgreeting-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Info
  x-api-slug: restapiv1-0accountaccountid-get
  description: "Returns basic information about a particular RingCentral customer
    account.\nApp Permission\nReadAccounts\nUser Permission\nReadCompanyInfo\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n401\nOAU-213\nToken not found\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Business Address
  x-api-slug: restapiv1-0accountaccountidbusinessaddress-get
  description: "Returns business address of a company.\nApp Permission\nReadAccounts\nUser
    Permission\nReadCompanyInfo\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin to extension
    required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidbusinessaddress-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get All Company Phone Numbers
  x-api-slug: restapiv1-0accountaccountidphonenumber-get
  description: "Returns the list of phone numbers assigned to RingCentral customer
    account. Both company-level and extension-level numbers are returned.\nApp Permission\nReadAccounts\nUser
    Permission\nReadCompanyPhoneNumbers\nUsage Plan Group\nHeavy\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [perPage] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource for parameter
    [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidphonenumber-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get All Company Phone Numbers
  x-api-slug: restapiv1-0accountaccountidphonenumber-get
  description: "Returns the list of phone numbers assigned to RingCentral customer
    account. Both company-level and extension-level numbers are returned.\nApp Permission\nReadAccounts\nUser
    Permission\nReadCompanyPhoneNumbers\nUsage Plan Group\nHeavy\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [perPage] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource for parameter
    [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidphonenumber-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get All Company Phone Numbers
  x-api-slug: restapiv1-0accountaccountidphonenumber-get
  description: "Returns the list of phone numbers assigned to RingCentral customer
    account. Both company-level and extension-level numbers are returned.\nApp Permission\nReadAccounts\nUser
    Permission\nReadCompanyPhoneNumbers\nUsage Plan Group\nHeavy\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [perPage] value is invalid\n\n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n403\nCMN-401\nIn order to call this API endpoint, application
    needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource for parameter
    [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidphonenumber-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Business Address
  x-api-slug: restapiv1-0accountaccountidbusinessaddress-get
  description: "Returns business address of a company.\nApp Permission\nReadAccounts\nUser
    Permission\nReadCompanyInfo\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin to extension
    required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidbusinessaddress-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Business Address
  x-api-slug: restapiv1-0accountaccountidbusinessaddress-get
  description: "Returns business address of a company.\nApp Permission\nReadAccounts\nUser
    Permission\nReadCompanyInfo\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin to extension
    required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidbusinessaddress-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Info
  x-api-slug: restapiv1-0accountaccountid-get
  description: "Returns basic information about a particular RingCentral customer
    account.\nApp Permission\nReadAccounts\nUser Permission\nReadCompanyInfo\nUsage
    Plan Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
    Message\n   \n \n\n401\nCMN-405\nLogin to extension required\n\n\n401\nOAU-151\nAuthorization
    method not supported\n\n\n401\nOAU-213\nToken not found\n\n\n403\nCMN-401\nIn
    order to call this API endpoint, application needs to have [ReadAccounts] permission\n\n\n404\nCMN-102\nResource
    for parameter [accountId] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Custom Company Greeting
  x-api-slug: restapiv1-0accountaccountidgreeting-post
  description: "Creates a custom company greeting.\nApp Permission\nEditAccounts\nUser
    Permission\nReadUserInfo\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-129\nInvalid attachment
    media type\n\n\n400\nAWR-178\nGreeting type [Voicemail] is not applicable to company
    rule\n\n\n400\nCMN-101\nParameter [type] value is invalid\n\n\n400\nCMN-102\nResource
    for parameter [answeringRule.id] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidgreeting-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Custom Company Greeting
  x-api-slug: restapiv1-0accountaccountidgreeting-post
  description: "Creates a custom company greeting.\nApp Permission\nEditAccounts\nUser
    Permission\nReadUserInfo\nUsage Plan Group\nMedium\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-129\nInvalid attachment
    media type\n\n\n400\nAWR-178\nGreeting type [Voicemail] is not applicable to company
    rule\n\n\n400\nCMN-101\nParameter [type] value is invalid\n\n\n400\nCMN-102\nResource
    for parameter [answeringRule.id] is not found"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidgreeting-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-put
  description: "Updates a company answering rule.\nApp Permission\nEditAccounts\nUser
    Permission\nEditCompanyAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-164\nRule
    type cannot be changed\n\n\n400\nAWR-170\nInvalid greeting type: preset with [CompanyGreeting]
    must be used\n\n\n400\nAWR-172\n[extension] must be specified for [Bypass] call
    handling action\n\n\n400\nAWR-173\n[extension] can be specified for [Bypass] call
    handling action only\n\n\n400\nAWR-179\n[name] is too long: up to 127 symbols
    supported\n\n\n400\nAWR-182\nOnly bypass action is available in multi-level IVR
    mode\n\n\n400\nCMN-101\nParameter [callHandlingAction] value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-put
  description: "Updates a company answering rule.\nApp Permission\nEditAccounts\nUser
    Permission\nEditCompanyAnsweringRules\nUsage Plan Group\nMedium\nError Codes\n\n
    \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nAWR-164\nRule
    type cannot be changed\n\n\n400\nAWR-170\nInvalid greeting type: preset with [CompanyGreeting]
    must be used\n\n\n400\nAWR-172\n[extension] must be specified for [Bypass] call
    handling action\n\n\n400\nAWR-173\n[extension] can be specified for [Bypass] call
    handling action only\n\n\n400\nAWR-179\n[name] is too long: up to 127 symbols
    supported\n\n\n400\nAWR-182\nOnly bypass action is available in multi-level IVR
    mode\n\n\n400\nCMN-101\nParameter [callHandlingAction] value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringruleruleid-get
  description: |-
    Returns a company answering rule by ID.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidansweringruleruleid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidansweringrule-get
  description: |-
    Returns a list of company answering rules.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Call Handling Rules
  x-api-slug: restapiv1-0accountaccountidansweringrule-get
  description: |-
    Returns a list of company answering rules.
    App Permission
    ReadAccounts
    User Permission
    ReadCompanyAnsweringRules
    Usage Plan Group
    Medium
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringrule-post
  description: "Creates a company answering rule for a particular caller ID.\nApp
    Permission\nEditAccounts\nUser Permission\nEditCompanyAnsweringRules\nUsage Plan
    Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n400\nAWR-106\nGreeting [Company] is duplicated\n\n\n400\nAWR-108\nOnly
    custom rule can be created\n\n\n400\nAWR-120\nBusiness Hours/After Hours schedule
    condition is allowed only with other answering rule conditions\n\n\n400\nAWR-121\nBusiness
    Hours not specified for current user\n\n\n400\nAWR-170\nInvalid greeting type:
    preset with [CompanyGreeting] must be used\n\n\n400\nAWR-172\n[extension] must
    be specified for [Bypass] call handling action\n\n\n400\nAWR-173\n[extension]
    can be specified for [Bypass] call handling action only\n\n\n400\nAWR-179\n[name]
    is too long: up to 127 symbols supported\n\n\n400\nAWR-182\nOnly bypass action
    is available in multi-level IVR mode\n\n\n400\nCMN-101\nParameter [callHandlingAction]
    value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Create Company Call Handling Rule
  x-api-slug: restapiv1-0accountaccountidansweringrule-post
  description: "Creates a company answering rule for a particular caller ID.\nApp
    Permission\nEditAccounts\nUser Permission\nEditCompanyAnsweringRules\nUsage Plan
    Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n400\nAWR-106\nGreeting [Company] is duplicated\n\n\n400\nAWR-108\nOnly
    custom rule can be created\n\n\n400\nAWR-120\nBusiness Hours/After Hours schedule
    condition is allowed only with other answering rule conditions\n\n\n400\nAWR-121\nBusiness
    Hours not specified for current user\n\n\n400\nAWR-170\nInvalid greeting type:
    preset with [CompanyGreeting] must be used\n\n\n400\nAWR-172\n[extension] must
    be specified for [Bypass] call handling action\n\n\n400\nAWR-173\n[extension]
    can be specified for [Bypass] call handling action only\n\n\n400\nAWR-179\n[name]
    is too long: up to 127 symbols supported\n\n\n400\nAWR-182\nOnly bypass action
    is available in multi-level IVR mode\n\n\n400\nCMN-101\nParameter [callHandlingAction]
    value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidansweringrule-post-openapi.md
- name: RingCentral Connect Platform API Explorer - Update Company Business Hours
  x-api-slug: restapiv1-0accountaccountidbusinesshours-put
  description: "Updates company hours when answering rules are to be applied.\nApp
    Permission\nEditExtensions\nUser Permission\nEditUserAnsweringRules\nUsage Plan
    Group\nMedium\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n
    \  \n \n\n400\nAWR-176\nAt least one time range for [monday] required\n\n\n400\nAWR-177\nTime
    ranges limit for [monday] exceeded\n\n\n400\nCMN-101\nParameter [schedule.weeklyRanges]
    value is invalid"
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidbusinesshours-put-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Business Hours
  x-api-slug: restapiv1-0accountaccountidbusinesshours-get
  description: |-
    Returns company hours when answering rules are to be applied.
    App Permission
    ReadAccounts
    User Permission
    ReadUserAnsweringRules
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0accountaccountidbusinesshours-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Info
  x-api-slug: restapiv1-0glipcompaniescompanyid-get
  description: |-
    Returns a company by ID.
    App Permission
    Glip
    User Permission
    Glip
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0glipcompaniescompanyid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0glipcompaniescompanyid-get-openapi.md
- name: RingCentral Connect Platform API Explorer - Get Company Info
  x-api-slug: restapiv1-0glipcompaniescompanyid-get
  description: |-
    Returns a company by ID.
    App Permission
    Glip
    User Permission
    Glip
    Usage Plan Group
    Light
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28867-developer-ringcentral-com.jpg
  humanURL: http://www.ringcentral.com
  baseURL: https://platform.ringcentral.com//
  tags: Telecommunications, ISP, Voice, Video Conferencing, Webinars, Relative Data,
    Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0glipcompaniescompanyid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/companies/master/_listings/ringcentral/restapiv1-0glipcompaniescompanyid-get-openapi.md
x-common:
- type: x-blog
  url: https://medium.com/ringcentral-developers
- type: x-blog-rss
  url: https://medium.com/feed/ringcentral-developers
- type: x-github
  url: https://github.com/ringcentral
- type: x-openapi
  url: https://netstorage.ringcentral.com/dpw/api-explorer/swagger-ring_basic.yml?v=20180816
- type: x-website
  url: http://www.ringcentral.com
- type: x-api-gallery
  url: http://reverb.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ringcentral.stack.network
- type: x-code
  url: https://developer.ringcentral.com/library/sdks.html
- type: x-crunchbase
  url: https://crunchbase.com/organization/ringcentral
- type: x-developer
  url: https://developer.ringcentral.com/
- type: x-documentation
  url: https://developer.ringcentral.com/api-explorer/latest/index.html?_ga=2.259782990.551967760.1534465156-1236351744.1533920460
- type: x-support
  url: https://developer.ringcentral.com/support.html
- type: x-twitter
  url: https://twitter.com/RingCentral
- type: x-website
  url: https://developer.ringcentral.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
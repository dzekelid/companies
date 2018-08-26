---
swagger: "2.0"
x-collection-name: LogMeIn
x-complete: 0
info:
  title: GoToAssist Remote Support Available Recordings
  description: "This method retrieves a list of all available recordings on the account.
    Only recordings which are available for transcoding or downloading will be returned.
    The recording IDs are always returned in the order in which the recordings were
    started (i.e., startTime order). The request must contain one or more of the following:
    accountKey, userKey or companyId. The list of recordings can be filtered by the
    request parameters listed below.\n\nNote: Session recording must be enabled on
    the account in order to use this API method. To enable session recording, log
    in at https://app.gotoassist.com (link is external) and go to Configure > GoToAssist
    Settings > Enable Session Recording check box.\n\n  Request Parameters                  \n
    \ Each request must contain one or more of the following: accountKey, userKey
    or companyId.                  \n                    \n    field      data type
    \     description    \n    accountKey      number      The account key associated
    with the recording ( available in the Get Screen Sharing Session Info (link is
    external) method response )    \n    userKey      number      The user key of
    the technician who started the recorded session (available in the Authentication
    (link is external) API method response)    \n    companyId      number      The
    companyId associated with the recording for unattended support sessions only (
    available in the Get Companies (link is external) API method response )    \n
    \   sessionType *      number      The type of session: attended (0) or unattended
    (1)    \n    fromTime *      ISO 8601 format **      The oldest sessions that
    should be retrieved (startTime must be greater than or equal to fromTime)    \n
    \   toTime *      ISO 8601 format **      The most recent sessions that should
    be retrieved (startTime must be greater than or equal to fromTime)    \n    timePeriod
    *      number      The recordings within a Time Period, starting from currentDate
    (ex: \u201DtimePeriod=30\u201D would retrieve the last 30 days\u2019 recordings)
    \   \n    archived *      number      The option to include only archived recordings,
    as follows: include only archived recordings (1) or include only non-archived
    recordings (0 or omit)    \n                    \n* Optional                    \n**
    ISO 8601 format reference                    \n                    \n  Response
    Parameters                  \n  No more than 500 recordings at a time will be
    returned for readyForTranscode or readyForDownload.                  \n                    \n
    \   field      data type      description    \n    readyForTranscode      array
    \     A list of recordingIds for recordings that are ready to be transcoded    \n
    \   readyForDownload      array      A list of recordingIds for recordings that
    are ready to be downloaded    \n                    \n                    \nStatus
    Codes                    \n                    \n    Staus Code      description
    \         \n    200 OK      Recordings retrieved successfully          \n    400
    Bad Request      Request may be malformed or property may be missing or invalid
    \         \n    403 Forbidden      Invalid authorization header or invalid userKey,
    accountKey or companyId          \n    500 Internal Server Error      Unexpected
    server error"
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
  /archive/recordings:
    get:
      summary: Available Recordings
      description: "This method retrieves a list of all available recordings on the
        account. Only recordings which are available for transcoding or downloading
        will be returned. The recording IDs are always returned in the order in which
        the recordings were started (i.e., startTime order). The request must contain
        one or more of the following: accountKey, userKey or companyId. The list of
        recordings can be filtered by the request parameters listed below.\n\nNote:
        Session recording must be enabled on the account in order to use this API
        method. To enable session recording, log in at https://app.gotoassist.com
        (link is external) and go to Configure > GoToAssist Settings > Enable Session
        Recording check box.\n\n  Request Parameters                  \n  Each request
        must contain one or more of the following: accountKey, userKey or companyId.
        \                 \n                    \n    field      data type      description
        \   \n    accountKey      number      The account key associated with the
        recording ( available in the Get Screen Sharing Session Info (link is external)
        method response )    \n    userKey      number      The user key of the technician
        who started the recorded session (available in the Authentication (link is
        external) API method response)    \n    companyId      number      The companyId
        associated with the recording for unattended support sessions only ( available
        in the Get Companies (link is external) API method response )    \n    sessionType
        *      number      The type of session: attended (0) or unattended (1)    \n
        \   fromTime *      ISO 8601 format **      The oldest sessions that should
        be retrieved (startTime must be greater than or equal to fromTime)    \n    toTime
        *      ISO 8601 format **      The most recent sessions that should be retrieved
        (startTime must be greater than or equal to fromTime)    \n    timePeriod
        *      number      The recordings within a Time Period, starting from currentDate
        (ex: \u201DtimePeriod=30\u201D would retrieve the last 30 days\u2019 recordings)
        \   \n    archived *      number      The option to include only archived
        recordings, as follows: include only archived recordings (1) or include only
        non-archived recordings (0 or omit)    \n                    \n* Optional
        \                   \n** ISO 8601 format reference                    \n                    \n
        \ Response Parameters                  \n  No more than 500 recordings at
        a time will be returned for readyForTranscode or readyForDownload.                  \n
        \                   \n    field      data type      description    \n    readyForTranscode
        \     array      A list of recordingIds for recordings that are ready to be
        transcoded    \n    readyForDownload      array      A list of recordingIds
        for recordings that are ready to be downloaded    \n                    \n
        \                   \nStatus Codes                    \n                    \n
        \   Staus Code      description          \n    200 OK      Recordings retrieved
        successfully          \n    400 Bad Request      Request may be malformed
        or property may be missing or invalid          \n    403 Forbidden      Invalid
        authorization header or invalid userKey, accountKey or companyId          \n
        \   500 Internal Server Error      Unexpected server error"
      operationId: ArchiveRecordingsGet
      x-api-path-slug: archiverecordings-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: userKey
      responses:
        200:
          description: OK
      tags:
      - Available
      - Recordings
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
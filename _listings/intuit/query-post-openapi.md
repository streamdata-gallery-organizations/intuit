---
swagger: "2.0"
x-collection-name: Intuit
x-complete: 0
info:
  title: QuickBooks Online V3 API Post Query
  description: |-
    Read all transfer objects using the 'Query' endpoint
    Method : POST
  version: 1.0.0
host: DefaultParameterValue
basePath: /v3/company/DefaultParameterValue
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /cdc:
    get:
      summary: Get CDC
      description: |-
        Retrive changed Bill and invoice objects since Aug10,2016
        Method - GET
      operationId: getCdc
      x-api-path-slug: cdc-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: changedSince
      - in: header
        name: Content-Type
      - in: query
        name: entities
      - in: header
        name: User-Agent
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Accounting
      - CDC
  /query:
    post:
      summary: Post Query
      description: |-
        Read all transfer objects using the 'Query' endpoint
        Method : POST
      operationId: postQuery
      x-api-path-slug: query-post
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: query
        name: minorversion
      - in: header
        name: User-Agent
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Accounting
      - Query
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
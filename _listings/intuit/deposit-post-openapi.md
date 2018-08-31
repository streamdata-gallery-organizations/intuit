---
swagger: "2.0"
x-collection-name: Intuit
x-complete: 0
info:
  title: QuickBooks Online V3 API Post Deposit
  description: |-
    Update a deposit object
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
  /estimate/163:
    get:
      summary: Get Estimate
      description: |-
        Read an Estimate object by Id
        Method : POST
      operationId: getEstimate163
      x-api-path-slug: estimate163-get
      parameters:
      - in: header
        name: Accept
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
      - Estimate
  /invoice:
    post:
      summary: Post Invoice
      description: |-
        Create an invoice object
        Method : POST
      operationId: postInvoice
      x-api-path-slug: invoice-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
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
      - Invoice
  /term:
    post:
      summary: Post Term
      description: |-
        Update a term object
        Method : POST

        Term object can't be deleted parmanently. It can only be deactived by setting the 'Active' attribute to false.
      operationId: postTerm
      x-api-path-slug: term-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: header
        name: User-Agent
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Accounting
      - Term
  /preferences:
    get:
      summary: Get Preferences
      description: |-
        Read the preference object
        Method : POST
      operationId: getPreferences
      x-api-path-slug: preferences-get
      parameters:
      - in: header
        name: Accept
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
      - Preferences
    post:
      summary: Post Preferences
      description: |-
        Update the preference object endpoint
        Method : POST
      operationId: postPreferences
      x-api-path-slug: preferences-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
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
      - Preferences
  /reports/InventoryValuationSummary:
    get:
      summary: Get Reports Inventory Valuation Summary
      description: |-
        Report - Inventory Valuation Summary
        Method : GET

        Docs - https://developer.intuit.com/docs/api/accounting/inventory%20valuation
      operationId: getReportsInventoryvaluationsummary
      x-api-path-slug: reportsinventoryvaluationsummary-get
      parameters:
      - in: header
        name: Accept
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
      - Reports
      - Inventory
      - Valuation
      - Summary
  /purchase:
    post:
      summary: Post Purchase
      description: |-
        Create a puchase object
        Method : POST
      operationId: postPurchase
      x-api-path-slug: purchase-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
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
      - Purchase
  /salesreceipt/181:
    get:
      summary: Get SaleS Receipt
      description: |-
        Create an salesreceipt object
        Method : POST
      operationId: getSalesreceipt181
      x-api-path-slug: salesreceipt181-get
      parameters:
      - in: header
        name: Accept
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
      - SaleS
      - Receipt
  /deposit:
    post:
      summary: Post Deposit
      description: |-
        Update a deposit object
        Method : POST
      operationId: postDeposit
      x-api-path-slug: deposit-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
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
      - Deposit
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
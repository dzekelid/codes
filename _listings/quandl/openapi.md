---
swagger: "2.0"
x-collection-name: Quandl
x-complete: 1
info:
  title: Quandl
  description: the-quandl-api
  version: 1.0.0
host: www.quandl.com
basePath: /api/v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /databases/{database_code}/codes:
    get:
      summary: Get Databases Database Code Codes
      description: You can download a list of all dataset codes in a database in a
        single call, by appending /codes to your database request. The call will return
        a ZIP file containing a CSV.
      operationId: databases.database_code.codes.get
      x-api-path-slug: databasesdatabase-codecodes-get
      parameters:
      - in: path
        name: database_code
        description: The unique database code on Quandl (ex
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Databases
      - Database
      - Code
      - Codes
---
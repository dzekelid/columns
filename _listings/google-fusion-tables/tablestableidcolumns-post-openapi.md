---
swagger: "2.0"
x-collection-name: Google Fusion Tables
x-complete: 0
info:
  title: Google Fusion Tables API Add Column
  description: Adds a new column to the table.
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /fusiontables/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tables/{tableId}/columns:
    get:
      summary: Get Columns
      description: Retrieves a list of columns.
      operationId: fusiontables.column.list
      x-api-path-slug: tablestableidcolumns-get
      parameters:
      - in: query
        name: maxResults
        description: Maximum number of columns to return
      - in: query
        name: pageToken
        description: Continuation token specifying which result page to return
      - in: path
        name: tableId
        description: Table whose columns are being listed
      responses:
        200:
          description: OK
      tags:
      - Column
    post:
      summary: Add Column
      description: Adds a new column to the table.
      operationId: fusiontables.column.insert
      x-api-path-slug: tablestableidcolumns-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: tableId
        description: Table for which a new column is being added
      responses:
        200:
          description: OK
      tags:
      - Column
  /tables/{tableId}/columns/{columnId}:
    delete:
      summary: Delete Column
      description: Deletes the specified column.
      operationId: fusiontables.column.delete
      x-api-path-slug: tablestableidcolumnscolumnid-delete
      parameters:
      - in: path
        name: columnId
        description: Name or identifier for the column being deleted
      - in: path
        name: tableId
        description: Table from which the column is being deleted
      responses:
        200:
          description: OK
      tags:
      - Column
    get:
      summary: Get Column
      description: Retrieves a specific column by its ID.
      operationId: fusiontables.column.get
      x-api-path-slug: tablestableidcolumnscolumnid-get
      parameters:
      - in: path
        name: columnId
        description: Name or identifier for the column that is being requested
      - in: path
        name: tableId
        description: Table to which the column belongs
      responses:
        200:
          description: OK
      tags:
      - Column
    patch:
      summary: Update Column
      description: Updates the name or type of an existing column. This method supports
        patch semantics.
      operationId: fusiontables.column.patch
      x-api-path-slug: tablestableidcolumnscolumnid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: columnId
        description: Name or identifier for the column that is being updated
      - in: path
        name: tableId
        description: Table for which the column is being updated
      responses:
        200:
          description: OK
      tags:
      - Column
    put:
      summary: Update Column
      description: Updates the name or type of an existing column.
      operationId: fusiontables.column.update
      x-api-path-slug: tablestableidcolumnscolumnid-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: columnId
        description: Name or identifier for the column that is being updated
      - in: path
        name: tableId
        description: Table for which the column is being updated
      responses:
        200:
          description: OK
      tags:
      - Column
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
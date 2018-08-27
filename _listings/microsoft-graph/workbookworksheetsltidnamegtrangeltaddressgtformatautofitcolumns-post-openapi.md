---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Range Format Autofit Columns
  description: 'RangeFormat: autofitColumns Changes the width of the columns of the
    current range to achieve the best fit, based on the current data in the columns.'
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workbook/names(&lt;name&gt;)/range/format/autofitColumns:
    post:
      summary: Range Format Autofit Columns
      description: 'RangeFormat: autofitColumns Changes the width of the columns of
        the current range to achieve the best fit, based on the current data in the
        columns.'
      operationId: RangeFormat:AutofitColumns
      x-api-path-slug: workbooknamesltnamegtrangeformatautofitcolumns-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Format
      - Autofit
      - Columns
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/autofitColumns:
    post:
      summary: Range Format Autofit Columns
      description: 'RangeFormat: autofitColumns Changes the width of the columns of
        the current range to achieve the best fit, based on the current data in the
        columns.'
      operationId: RangeFormat:AutofitColumns
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatautofitcolumns-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Format
      - Autofit
      - Columns
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
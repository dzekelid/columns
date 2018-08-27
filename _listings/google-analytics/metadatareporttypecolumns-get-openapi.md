---
swagger: "2.0"
x-collection-name: Google Analytics
x-complete: 0
info:
  title: Google Analytics Get Columsn
  description: Lists all columns for a report type
  contact:
    name: Google
    url: https://google.com
  version: v3
host: www.googleapis.com
basePath: /analytics/v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /metadata/{reportType}/columns:
    get:
      summary: Get Columsn
      description: Lists all columns for a report type
      operationId: analytics.metadata.columns.list
      x-api-path-slug: metadatareporttypecolumns-get
      parameters:
      - in: path
        name: reportType
        description: Report type
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
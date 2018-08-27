swagger: "2.0"
x-collection-name: Google Analytics
x-complete: 1
info:
  title: Google Analytics
  description: views-and-manages-your-google-analytics-data-
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
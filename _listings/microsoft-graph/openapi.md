---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
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
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/autofitColumns:
    post:
      summary: Range Format Autofit Columns
      description: 'RangeFormat: autofitColumns Changes the width of the columns of
        the current range to achieve the best fit, based on the current data in the
        columns.'
      operationId: RangeFormat:AutofitColumns
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatautofitcolumns-post
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
  /workbook/tables(&lt;id|name&gt;)/columns:
    get:
      summary: List Columns
      description: List columns Retrieve a list of tablecolumn objects.
      operationId: ListColumns
      x-api-path-slug: workbooktablesltidnamegtcolumns-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - List
      - Columns
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns:
    get:
      summary: List Columns
      description: List columns Retrieve a list of tablecolumn objects.
      operationId: ListColumns
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumns-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - List
      - Columns
---
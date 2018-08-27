---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Table Column Header Row Range
  description: 'TableColumn: HeaderRowRange Gets the range object associated with
    the header row of the column.'
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
    post:
      summary: Create Table Column
      description: Create TableColumn Use this API to create a new TableColumn.
      operationId: CreateTableColumn
      x-api-path-slug: workbooktablesltidnamegtcolumns-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
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
    post:
      summary: Create Table Column
      description: Create TableColumn Use this API to create a new TableColumn.
      operationId: CreateTableColumn
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumns-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
  /workbook/names(&lt;name&gt;)/range/Column:
    post:
      summary: Range Column
      description: 'Range: Column Gets a column contained in the range.'
      operationId: Range:Column
      x-api-path-slug: workbooknamesltnamegtrangecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Column
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/Column:
    post:
      summary: Range Column
      description: 'Range: Column Gets a column contained in the range.'
      operationId: Range:Column
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtcolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Column
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/Column:
    post:
      summary: Range Column
      description: 'Range: Column Gets a column contained in the range.'
      operationId: Range:Column
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Column
  /workbook/names(&lt;name&gt;)/range/EntireColumn:
    post:
      summary: Range Entire Column
      description: 'Range: EntireColumn Gets an object that represents the entire
        column of the range.'
      operationId: Range:EntireColumn
      x-api-path-slug: workbooknamesltnamegtrangeentirecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
      - Column
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/EntireColumn:
    post:
      summary: Range Entire Column
      description: 'Range: EntireColumn Gets an object that represents the entire
        column of the range.'
      operationId: Range:EntireColumn
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtentirecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
      - Column
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/EntireColumn:
    post:
      summary: Range Entire Column
      description: 'Range: EntireColumn Gets an object that represents the entire
        column of the range.'
      operationId: Range:EntireColumn
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeentirecolumn-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Range
      - Entire
      - Column
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/DataBodyRange:
    post:
      summary: Table Column Data Body Range
      description: 'TableColumn: DataBodyRange Gets the range object associated with
        the data body of the column.'
      operationId: TableColumn:DataBodyRange
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtdatabodyrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Data
      - Body
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/DataBodyRange:
    post:
      summary: Table Column Data Body Range
      description: 'TableColumn: DataBodyRange Gets the range object associated with
        the data body of the column.'
      operationId: TableColumn:DataBodyRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtdatabodyrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Data
      - Body
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/delete:
    post:
      summary: Table Column Delete
      description: 'TableColumn: delete Deletes the column from the table.'
      operationId: TableColumn:Delete
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtdelete-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/delete:
    post:
      summary: Table Column Delete
      description: 'TableColumn: delete Deletes the column from the table.'
      operationId: TableColumn:Delete
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtdelete-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;):
    get:
      summary: Get Table Column
      description: Get TableColumn Retrieve the properties and relationships of tablecolumn
        object.
      operationId: GetTableColumn
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegt-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;):
    get:
      summary: Get Table Column
      description: Get TableColumn Retrieve the properties and relationships of tablecolumn
        object.
      operationId: GetTableColumn
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegt-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/HeaderRowRange:
    post:
      summary: Table Column Header Row Range
      description: 'TableColumn: HeaderRowRange Gets the range object associated with
        the header row of the column.'
      operationId: TableColumn:HeaderRowRange
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtheaderrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Header
      - Row
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/HeaderRowRange:
    post:
      summary: Table Column Header Row Range
      description: 'TableColumn: HeaderRowRange Gets the range object associated with
        the header row of the column.'
      operationId: TableColumn:HeaderRowRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtheaderrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Header
      - Row
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/Range:
    post:
      summary: Table Column Range
      description: 'TableColumn: Range Gets the range object associated with the entire
        column.'
      operationId: TableColumn:Range
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/Range:
    post:
      summary: Table Column Range
      description: 'TableColumn: Range Gets the range object associated with the entire
        column.'
      operationId: TableColumn:Range
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegtrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/TotalRowRange:
    post:
      summary: Table Column Total Row Range
      description: 'TableColumn: TotalRowRange Gets the range object associated with
        the totals row of the column.'
      operationId: TableColumn:TotalRowRange
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegttotalrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Total
      - Row
      - Range
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/TotalRowRange:
    post:
      summary: Table Column Total Row Range
      description: 'TableColumn: TotalRowRange Gets the range object associated with
        the totals row of the column.'
      operationId: TableColumn:TotalRowRange
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsltidnamegttotalrowrange-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Total
      - Row
      - Range
  /workbook/tables(&lt;id|name&gt;)/columns/add:
    post:
      summary: Table Column Collection Add
      description: 'TableColumnCollection: add Adds a new column to the table.'
      operationId: TableColumnCollection:Add
      x-api-path-slug: workbooktablesltidnamegtcolumnsadd-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Collection
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns/add:
    post:
      summary: Table Column Collection Add
      description: 'TableColumnCollection: add Adds a new column to the table.'
      operationId: TableColumnCollection:Add
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsadd-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Collection
  /workbook/tables(&lt;id|name&gt;)/columns/ItemAt:
    post:
      summary: Table Column Collection Item At
      description: 'TableColumnCollection: ItemAt Gets a column based on its position
        in the collection.'
      operationId: TableColumnCollection:ItemAt
      x-api-path-slug: workbooktablesltidnamegtcolumnsitemat-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Collection
      - Item
      - At
  /workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns/ItemAt:
    post:
      summary: Table Column Collection Item At
      description: 'TableColumnCollection: ItemAt Gets a column based on its position
        in the collection.'
      operationId: TableColumnCollection:ItemAt
      x-api-path-slug: workbookworksheetsltidnamegttablesltidnamegtcolumnsitemat-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Table
      - Column
      - Collection
      - Item
      - At
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
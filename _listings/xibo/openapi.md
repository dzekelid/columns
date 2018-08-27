swagger: "2.0"
x-collection-name: Xibo
x-complete: 1
info:
  title: Xibo API
  description: xibo-cms-api
  termsOfService: http://xibo.org.uk/legal
  version: 1.0.0
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /dataset/{dataSetId}/column:
    get:
      summary: Search Columns
      description: Search Columns for DataSet
      operationId: dataSetColumnSearch
      x-api-path-slug: datasetdatasetidcolumn-get
      parameters:
      - in: formData
        name: dataSetColumnId
        description: Filter by DataSet ColumnID
      - in: path
        name: dataSetId
        description: The DataSet ID
      responses:
        200:
          description: OK
      tags:
      - Search
      - Columns
    post:
      summary: Add Column
      description: Add a Column to a DataSet
      operationId: dataSetColumnAdd
      x-api-path-slug: datasetdatasetidcolumn-post
      parameters:
      - in: formData
        name: columnOrder
        description: The display order for this column
      - in: formData
        name: dataSetColumnTypeId
        description: The column type for this column
      - in: path
        name: dataSetId
        description: The DataSet ID
      - in: formData
        name: dataTypeId
        description: The data type ID for this column
      - in: formData
        name: formula
        description: MySQL SELECT syntax formula for this Column if the column type
          is formula
      - in: formData
        name: heading
        description: The heading for the Column
      - in: formData
        name: listContent
        description: A comma separated list of content for drop downs
      - in: formData
        name: remoteField
        description: JSON-String to select Data from the Remote DataSet
      - in: formData
        name: showFilter
        description: Flag indicating whether this column should present a filter on
          DataEntry
      - in: formData
        name: showSort
        description: Flag indicating whether this column should allow sorting on DataEntry
      responses:
        200:
          description: OK
      tags:
      - Column
  /dataset/{dataSetId}/column/{dataSetColumnId}:
    put:
      summary: Edit Column
      description: Edit a Column to a DataSet
      operationId: dataSetColumnEdit
      x-api-path-slug: datasetdatasetidcolumndatasetcolumnid-put
      parameters:
      - in: formData
        name: columnOrder
        description: The display order for this column
      - in: path
        name: dataSetColumnId
        description: The Column ID
      - in: formData
        name: dataSetColumnTypeId
        description: The column type for this column
      - in: path
        name: dataSetId
        description: The DataSet ID
      - in: formData
        name: dataTypeId
        description: The data type ID for this column
      - in: formData
        name: formula
        description: MySQL SELECT syntax formula for this Column if the column type
          is formula
      - in: formData
        name: heading
        description: The heading for the Column
      - in: formData
        name: listContent
        description: A comma separated list of content for drop downs
      - in: formData
        name: remoteField
        description: JSON-String to select Data from the Remote DataSet
      - in: formData
        name: showFilter
        description: Flag indicating whether this column should present a filter on
          DataEntry
      - in: formData
        name: showSort
        description: Flag indicating whether this column should allow sorting on DataEntry
      responses:
        200:
          description: OK
      tags:
      - Edit
      - Column
    delete:
      summary: Delete Column
      description: Delete DataSet Column
      operationId: dataSetColumnDelete
      x-api-path-slug: datasetdatasetidcolumndatasetcolumnid-delete
      parameters:
      - in: path
        name: dataSetColumnId
        description: The Column ID
      - in: path
        name: dataSetId
        description: The DataSet ID
      responses:
        200:
          description: OK
      tags:
      - Column
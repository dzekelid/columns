---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Updates a specific column.
  description: Updates a specific column..
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/boards/{boardId}/columns/{columnId}/position:
    put:
      summary: Updates the position of a specific column. Also updates the positions
        of all following columns on the same board.
      description: Updates the position of a specific column. also updates the positions
        of all following columns on the same board..
      operationId: putRestBoardsBoardColumnsColumnPosition
      x-api-path-slug: restboardsboardidcolumnscolumnidposition-put
      parameters:
      - in: path
        name: boardId
      - in: path
        name: columnId
      - in: query
        name: position
      responses:
        200:
          description: OK
      tags:
      - S
      - Position
      - Of
      - Specific
      - Column
      - ""
      - Also
      - Updates
      - Positions
      - Of
      - ""
      - Following
      - Columns
      - "On"
      - Same
      - Board
  /rest/boards/{boardId}/columns:
    post:
      summary: Creates a new column and assigns it to a given board
      description: Creates a new column and assigns it to a given board.
      operationId: postRestBoardsBoardColumns
      x-api-path-slug: restboardsboardidcolumns-post
      parameters:
      - in: body
        name: /rest/boards/{boardId}/columns
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: boardId
      responses:
        200:
          description: OK
      tags:
      - Creates
      - New
      - Column
      - Assigns
      - It
      - To
      - Given
      - Board
  /rest/boards/{boardId}/columns/{columnId}:
    delete:
      summary: Deletes a specific column.
      description: Deletes a specific column..
      operationId: deleteRestBoardsBoardColumnsColumn
      x-api-path-slug: restboardsboardidcolumnscolumnid-delete
      parameters:
      - in: path
        name: boardId
      - in: path
        name: columnId
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Column
    post:
      summary: Copies a specific column.
      description: Copies a specific column..
      operationId: postRestBoardsBoardColumnsColumn
      x-api-path-slug: restboardsboardidcolumnscolumnid-post
      parameters:
      - in: path
        name: boardId
      - in: path
        name: columnId
      responses:
        200:
          description: OK
      tags:
      - Copies
      - Specific
      - Column
    put:
      summary: Updates a specific column.
      description: Updates a specific column..
      operationId: putRestBoardsBoardColumnsColumn
      x-api-path-slug: restboardsboardidcolumnscolumnid-put
      parameters:
      - in: body
        name: /rest/boards/{boardId}/columns/{columnId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: boardId
      - in: path
        name: columnId
      responses:
        200:
          description: OK
      tags:
      - S
      - Specific
      - Column
  /rest/boards/{boardId}/columns/{columnId}/tasks:
    get:
      summary: Lists all tasks for a given column.
      description: Lists all tasks for a given column..
      operationId: getRestBoardsBoardColumnsColumnTasks
      x-api-path-slug: restboardsboardidcolumnscolumnidtasks-get
      parameters:
      - in: path
        name: boardId
      - in: path
        name: columnId
      - in: query
        name: startAt
        description: Position of a task to start listing at
      - in: query
        name: tasksPerPage
        description: Number of tasks to list per page
      responses:
        200:
          description: OK
      tags:
      - Lists
      - ""
      - Tasksa
      - Given
      - Column
    post:
      summary: Creates a new tasks on a specified column.
      description: Creates a new tasks on a specified column..
      operationId: postRestBoardsBoardColumnsColumnTasks
      x-api-path-slug: restboardsboardidcolumnscolumnidtasks-post
      parameters:
      - in: body
        name: /rest/boards/{boardId}/columns/{columnId}/tasks
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: boardId
      - in: path
        name: columnId
      responses:
        200:
          description: OK
      tags:
      - Creates
      - New
      - Tasks
      - "On"
      - Specified
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
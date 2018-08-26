---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
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
---
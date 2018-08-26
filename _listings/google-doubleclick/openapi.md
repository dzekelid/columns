---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 1
info:
  title: Google Doubleclick Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /agency/{agencyId}/advertiser/{advertiserId}/savedcolumns:
    get:
      summary: Get Saved Columns
      description: Retrieve the list of saved columns for a specified advertiser.
      operationId: doubleclicksearch.savedColumns.list
      x-api-path-slug: agencyagencyidadvertiseradvertiseridsavedcolumns-get
      parameters:
      - in: path
        name: advertiserId
        description: DS ID of the advertiser
      - in: path
        name: agencyId
        description: DS ID of the agency
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Colum
---
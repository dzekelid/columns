---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 0
info:
  title: Google Doubleclick API Get Saved Columns
  version: 1.0.0
  description: Retrieve the list of saved columns for a specified advertiser.
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
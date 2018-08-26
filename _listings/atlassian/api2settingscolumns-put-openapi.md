---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Cloud API Set issue navigator default columns
  description: Sets the default system columns for issue navigator. Admin permission
    will be required.
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/filter/{id}/columns:
    get:
      summary: Get columns
      description: Returns the columns configured for a filter. The column configuration
        is used when the filter's results are viewed in _List View_ with the _Columns_
        set to _Filter_. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
        required:** None, however the calling user must have permission to view the
        filter.
      operationId: com.atlassian.jira.rest.v2.search.FilterResource.getColumns_get
      x-api-path-slug: api2filteridcolumns-get
      parameters:
      - in: path
        name: id
        description: The ID of the filter
      responses:
        200:
          description: OK
      tags:
      - Columns
    put:
      summary: Set columns
      description: Sets the columns for a filter. Only navigable fields can be set
        as columns. Use [Get fields](https://developer.atlassian.com/cloud/jira/platform/rest#api-api-2-field-get)
        to get the list fields in Jira. A navigable field has `navigable` set to `true`.
        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission
        to log in to Jira (i.e., member of the _users_ [group](https://confluence.atlassian.com/x/24xjL))
        and permission to view the filter.
      operationId: com.atlassian.jira.rest.v2.search.FilterResource.setColumns_put
      x-api-path-slug: api2filteridcolumns-put
      parameters:
      - in: path
        name: id
        description: The ID of the filter
      responses:
        200:
          description: OK
      tags:
      - Set
      - Columns
    delete:
      summary: Reset columns
      description: Reset the user's column configuration for the filter to the default.
        **[Permissions](https://confluence.atlassian.com/x/FQiiLQ) required:** Permission
        to log in to Jira (i.e., member of the _users_ [group](https://confluence.atlassian.com/x/24xjL))
        and permission to view the filter.
      operationId: com.atlassian.jira.rest.v2.search.FilterResource.resetColumns_delete
      x-api-path-slug: api2filteridcolumns-delete
      parameters:
      - in: path
        name: id
        description: The ID of the filter
      responses:
        200:
          description: OK
      tags:
      - Reset
      - Columns
  /api/2/settings/columns:
    get:
      summary: Get issue navigator default columns
      description: Returns the default system columns for issue navigator. Admin permission
        will be required.
      operationId: com.atlassian.jira.rest.v2.admin.SettingsResource.getIssueNavigatorDefaultColumns_get
      x-api-path-slug: api2settingscolumns-get
      responses:
        200:
          description: OK
      tags:
      - Issue
      - Navigator
      - Default
      - Columns
    put:
      summary: Set issue navigator default columns
      description: Sets the default system columns for issue navigator. Admin permission
        will be required.
      operationId: com.atlassian.jira.rest.v2.admin.SettingsResource.setIssueNavigatorDefaultColumns_put
      x-api-path-slug: api2settingscolumns-put
      responses:
        200:
          description: OK
      tags:
      - Set
      - Issue
      - Navigator
      - Default
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
---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Columns
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/columns/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph Range Format Autofit Columns
  x-api-slug: microsoft-graph
  description: 'RangeFormat: autofitColumns Changes the width of the columns of the
    current range to achieve the best fit, based on the current data in the columns.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/autofitColumns
  tags: Range, Format, Autofit, Columns
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/columns/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatautofitcolumns-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/columns/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatautofitcolumns-post-openapi.md
- name: Microsoft Graph Range Format Autofit Columns
  x-api-slug: microsoft-graph
  description: 'RangeFormat: autofitColumns Changes the width of the columns of the
    current range to achieve the best fit, based on the current data in the columns.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/autofitColumns
  tags: Range, Format, Autofit, Columns
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/columns/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatautofitcolumns-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/columns/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatautofitcolumns-post-openapi.md
- name: Microsoft Graph Range Format Autofit Columns
  x-api-slug: microsoft-graph
  description: 'RangeFormat: autofitColumns Changes the width of the columns of the
    current range to achieve the best fit, based on the current data in the columns.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/autofitColumns
  tags: Range, Format, Autofit, Columns
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/columns/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatautofitcolumns-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/columns/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatautofitcolumns-post-openapi.md
- name: Microsoft Graph List Columns
  x-api-slug: microsoft-graph
  description: List columns Retrieve a list of tablecolumn objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns
  tags: List, Columns
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/columns/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/columns/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumns-get-openapi.md
- name: Microsoft Graph List Columns
  x-api-slug: microsoft-graph
  description: List columns Retrieve a list of tablecolumn objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/columns
  tags: List, Columns
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/columns/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/columns/master/_listings/microsoft-graph/workbookworksheetsltidnamegttablesltidnamegtcolumns-get-openapi.md
- name: Microsoft Graph
  x-api-slug: microsoft-graph
  description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
    cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
    Graph simplifies queries that would otherwise be more complex. You can use Microsoft
    Graph to: Access data from multiple Microsoft cloud services, including Azure
    Active Directory, Exchange Online as part of Office 365, SharePoint, OneDrive,
    OneNote, and Planner. Navigate between entities and relationships. Access intelligence
    and insights from the Microsoft cloud (for commercial users).'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Columns
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/columns/master/_listings/microsoft-graph/openapi.md
x-common:
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
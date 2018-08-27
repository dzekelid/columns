{
  "info": {
    "name": "Microsoft Graph API Range Format Autofit Columns",
    "_postman_id": "3bd605fa-3924-4c31-a958-a9525707afa3",
    "description": "RangeFormat: autofitColumns Changes the width of the columns of the current range to achieve the best fit, based on the current data in the columns.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "range",
      "item": [
        {
          "id": "9efe4d23-7a68-478b-ab4b-796f7ed6e85d",
          "name": "RangeFormat:AutofitColumns",
          "request": {
            "url": "http://graph.microsoft.com/workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/autofitColumns",
            "method": "POST",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "RangeFormat: autofitColumns Changes the width of the columns of the current range to achieve the best fit, based on the current data in the columns"
          },
          "response": [
            {
              "status": "Successful Response",
              "code": 200,
              "name": "Response_200",
              "id": "ceb5734b-5394-4a7a-b430-ea95c0f2fd3d"
            }
          ]
        }
      ]
    }
  ]
}
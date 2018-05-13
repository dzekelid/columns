{
  "info": {
    "name": "Microsoft Graph API Range Format Autofit Columns",
    "_postman_id": "13f083b3-db37-4b4c-900a-f215239a32cc",
    "description": "RangeFormat: autofitColumns Changes the width of the columns of the current range to achieve the best fit, based on the current data in the columns.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "range",
      "item": [
        {
          "id": "7b044d02-6485-4dc6-abee-fb758456fcaa",
          "name": "RangeFormat:AutofitColumns",
          "request": {
            "url": "http://graph.microsoft.com/workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/autofitColumns",
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
              "id": "e698661c-72a5-4b2e-842f-499d6682721a"
            }
          ]
        }
      ]
    }
  ]
}
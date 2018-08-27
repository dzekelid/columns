{
  "info": {
    "name": "Microsoft Graph API Range Format Autofit Columns",
    "_postman_id": "3657c9db-babb-4e03-b4ea-ce7969276bfd",
    "description": "RangeFormat: autofitColumns Changes the width of the columns of the current range to achieve the best fit, based on the current data in the columns.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "range",
      "item": [
        {
          "id": "d681bac9-2e88-4d63-9310-18c69821a91c",
          "name": "RangeFormat:AutofitColumns",
          "request": {
            "url": "http://graph.microsoft.com/workbook/names(&lt;name&gt;)/range/format/autofitColumns",
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
              "id": "615d825b-2eae-4c71-8684-7a5f0531d23f"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "QuickBooks Online V3 API Get CDC",
    "_postman_id": "8077089c-3aca-4412-9721-28f1f0ff1ea8",
    "description": "Retrive changed Bill and invoice objects since Aug10,2016\nMethod - GET",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Accounting",
      "item": [
        {
          "id": "35052123-9786-4f96-8bd4-1f5099f98d99",
          "name": "getCdc",
          "request": {
            "url": "http://DefaultParameterValue/v3/company/DefaultParameterValue/cdc?changedSince=%7B%7D&entities=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "User-Agent",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Retrive changed Bill and invoice objects since Aug10,2016\nMethod - GET"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c9ef53b7-9d6e-4188-b512-b4ee7ddb5a6d"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "QuickBooks Online V3 API Post Query",
    "_postman_id": "302285be-85bc-429b-98cd-28ee7927cbaa",
    "description": "Read all transfer objects using the 'Query' endpoint\nMethod : POST",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Accounting",
      "item": [
        {
          "id": "ab1dec72-ba8d-44b5-ad47-377eb4708f9c",
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
              "id": "84e1eee5-4259-4cd0-a5ad-7ec2e528a780"
            }
          ]
        },
        {
          "id": "5f7ffad0-5ee6-49dc-bff3-ec919c174b20",
          "name": "postQuery",
          "request": {
            "url": "http://DefaultParameterValue/v3/company/DefaultParameterValue/query?minorversion=%7B%7D",
            "method": "POST",
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
            "description": "Read all transfer objects using the 'Query' endpoint\nMethod : POST"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "13657287-0d10-4f52-aced-65760be8fc30"
            }
          ]
        }
      ]
    }
  ]
}
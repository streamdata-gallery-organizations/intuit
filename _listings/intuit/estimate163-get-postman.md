{
  "info": {
    "name": "QuickBooks Online V3 API Get Estimate",
    "_postman_id": "0e9d22c6-a53b-4ec6-997c-fb5dbdb70917",
    "description": "Read an Estimate object by Id\nMethod : POST",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Accounting",
      "item": [
        {
          "id": "38cdcf07-ddc4-4db4-8843-50b5be47e08c",
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
              "id": "13c94bc3-4e2a-4884-a1f7-c763ed28d128"
            }
          ]
        },
        {
          "id": "6f3b6982-a19d-458f-94e8-9b223efc78e6",
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
              "id": "28e9b6be-bd6b-475b-9a84-d816ce30f6b3"
            }
          ]
        },
        {
          "id": "edc734de-7ff6-4443-9a86-e26aeb6030c2",
          "name": "getEstimate163",
          "request": {
            "url": "http://DefaultParameterValue/v3/company/DefaultParameterValue/estimate/163?minorversion=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
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
            "description": "Read an Estimate object by Id\nMethod : POST"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "12f8e894-307f-4a22-9fd3-dd50a999b1fd"
            }
          ]
        }
      ]
    }
  ]
}
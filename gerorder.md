Get Order Statuses

# Get Order Statuses

Retrieve the list of all possible statuses that can be assigned to an order.

# OpenAPI definition

```json
{
  "openapi": "3.1.0",
  "info": {
    "title": "orderry-public-api",
    "version": "1.3"
  },
  "servers": [
    {
      "url": "https://api.orderry.com"
    }
  ],
  "components": {
    "securitySchemes": {
      "sec0": {
        "type": "oauth2",
        "flows": {}
      }
    }
  },
  "security": [
    {
      "sec0": []
    }
  ],
  "paths": {
    "/statuses/orders": {
      "get": {
        "summary": "Get Order Statuses",
        "description": "Retrieve the list of all possible statuses that can be assigned to an order.",
        "operationId": "get-order-statuses",
        "responses": {
          "200": {
            "description": "200",
            "content": {
              "application/json": {
                "examples": {
                  "Result": {
                    "value": "{}"
                  }
                },
                "schema": {
                  "type": "object",
                  "properties": {}
                }
              }
            }
          },
          "400": {
            "description": "400",
            "content": {
              "application/json": {
                "examples": {
                  "Result": {
                    "value": "{}"
                  }
                },
                "schema": {
                  "type": "object",
                  "properties": {}
                }
              }
            }
          }
        },
        "deprecated": false
      }
    }
  },
  "x-readme": {
    "headers": [],
    "explorer-enabled": true,
    "proxy-enabled": true
  },
  "x-readme-fauxas": true
}
```

# OpenAPI definition
```json
{
  "_id": "/branches/1.3/apis/orderry-public-api.json",
  "openapi": "3.1.0",
  "info": {
    "title": "orderry-public-api",
    "version": "1.3"
  },
  "servers": [
    {
      "url": "https://api.orderry.com"
    }
  ],
  "components": {
    "securitySchemes": {
      "sec0": {
        "type": "oauth2",
        "flows": {}
      }
    }
  },
  "security": [
    {
      "sec0": []
    }
  ],
  "paths": {
    "/statuses/orders": {
      "get": {
        "summary": "Get Order Statuses",
        "description": "Retrieve the list of all possible statuses that can be assigned to an order.",
        "operationId": "get-order-statuses",
        "responses": {
          "200": {
            "description": "200",
            "content": {
              "application/json": {
                "examples": {
                  "Result": {
                    "value": "{}"
                  }
                },
                "schema": {
                  "type": "object",
                  "properties": {}
                }
              }
            }
          },
          "400": {
            "description": "400",
            "content": {
              "application/json": {
                "examples": {
                  "Result": {
                    "value": "{}"
                  }
                },
                "schema": {
                  "type": "object",
                  "properties": {}
                }
              }
            }
          }
        },
        "deprecated": false
      }
    }
  },
  "x-readme": {
    "headers": [],
    "explorer-enabled": true,
    "proxy-enabled": true
  },
  "x-readme-fauxas": true
}
```

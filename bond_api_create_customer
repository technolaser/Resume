Create a customer

---
agentTools:
  projectIndex: https://docs.bond.tech/llms.txt
---

# Create a customer

Creates a customer

**Doc References** <a href="doc:customer" target="_blank">Customers</a> <a href="doc:creating-a-customer-resource" target="_blank">Creating a customer</a>

# OpenAPI definition

```json
{
  "openapi": "3.0.0",
  "paths": {
    "/customers/": {
      "post": {
        "responses": {
          "201": {
            "description": "Successful response\n",
            "content": {
              "application/json": {
                "schema": {
                  "$ref": "#/components/schemas/customer"
                },
                "examples": {
                  "example": {
                    "value": {
                      "customer_id": "b3f7f6c9-503e-4457-b0ca-31f65131cfff",
                      "bond_brand_id": "8c7e08c8-0320-444c-b834-007cd9e18c0e",
                      "dob": "1997-12-25",
                      "first_name": "James",
                      "middle_name": "Herbert",
                      "last_name": "Bond",
                      "ssn": "XXX-XX-9999",
                      "phone": "555-111-2222",
                      "phone_country_code": "1",
                      "email": "james@mi6.gov.uk",
                      "addresses": [
                        {
                          "address_id": "5ff2a5f8-2d96-4c89-9edc-ec762ac3844c",
                          "address_type": "MAILING",
                          "street": "345 California Ave.",
                          "street2": "Suite 600",
                          "city": "San Francisco",
                          "state": "CA",
                          "zip_code": "12345-1234",
                          "country": "US",
                          "is_primary": true,
                          "date_created": "2021-10-11T17:54:26.784367+00:00"
                        }
                      ],
                      "date_created": "2021-06-02T13:38:27.965404+00:00"
                    }
                  }
                }
              }
            }
          }
        },
        "summary": "Create a customer",
        "description": "Creates a customer",
        "operationId": "post_customers",
        "requestBody": {
          "content": {
            "application/json": {
              "schema": {
                "$ref": "#/components/schemas/customer-write"
              },
              "examples": {
                "example": {
                  "value": {
                    "dob": "1997-12-25",
                    "first_name": "James",
                    "middle_name": "Herbert",
                    "last_name": "Bond",
                    "ssn": "XXX-XX-9999",
                    "phone": "555-111-2222",
                    "phone_country_code": "1",
                    "email": "james@mi6.gov.uk",
                    "addresses": [
                      {
                        "address_type": "MAILING",
                        "street": "345 California Ave.",
                        "street2": "Suite 600",
                        "city": "San Francisco",
                        "state": "CA",
                        "zip_code": "12345-1234",
                        "country": "US",
                        "is_primary": true
                      }
                    ]
                  }
                }
              }
            }
          },
          "required": true,
          "description": ""
        },
        "tags": [
          "Customers"
        ]
      }
    }
  },
  "info": {
    "title": "Customer",
    "version": "0",
    "description": "Studio customers"
  },
  "security": [
    {
      "identity": [],
      "authorization": []
    }
  ],
  "x-samples-languages": [
    "curl",
    "node",
    "ruby",
    "javascript",
    "python",
    "csharp",
    "java"
  ],
  "servers": [
    {
      "url": "https://sandbox.bond.tech/api/v0"
    }
  ],
  "components": {
    "securitySchemes": {
      "identity": {
        "type": "apiKey",
        "in": "header",
        "name": "Identity"
      },
      "authorization": {
        "type": "apiKey",
        "in": "header",
        "name": "Authorization"
      }
    },
    "schemas": {
      "customer": {
        "type": "object",
        "x-examples": {
          "example": {
            "customer_id": "b3f7f6c9-503e-4457-b0ca-31f65131cfff",
            "brand_person_id": "ac6ee2d3-5a03-4043-a4aa-dda51836b9fd",
            "bond_brand_id": "8c7e08c8-0320-444c-b834-007cd9e18c0e",
            "dob": "1997-12-25",
            "first_name": "James",
            "middle_name": "Herbert",
            "last_name": "Bond",
            "ssn": "XXX-XX-9999",
            "phone": "555-111-2222",
            "phone_country_code": "1",
            "email": "james@mi6.gov.uk",
            "addresses": [
              {
                "address_type": "MAILING",
                "street": "345 California Ave.",
                "street2": "Suite 600",
                "city": "San Francisco",
                "state": "CA",
                "zip_code": "12345-1234",
                "country": "US",
                "is_primary": true,
                "date_created": "2021-10-11T17:54:26.784367+00:00"
              }
            ],
            "date_created": "2021-06-02T13:38:27.965404+00:00"
          }
        },
        "title": "Customer",
        "properties": {
          "customer_id": {
            "type": "string",
            "example": "b3f7f6c9-503e-4457-b0ca-31f65131cfff",
            "readOnly": true
          },
          "brand_person_id": {
            "type": "string",
            "example": "ac6ee2d3-5a03-4043-a4aa-dda51836b9fd",
            "readOnly": true
          },
          "bond_brand_id": {
            "type": "string",
            "example": "8c7e08c8-0320-444c-b834-007cd9e18c0e",
            "readOnly": true
          },
          "business_id": {
            "type": "string",
            "example": "null",
            "nullable": true,
            "readOnly": true
          },
          "dob": {
            "type": "string",
            "format": "string",
            "description": "Birthday in YYYY-MM-DD format.",
            "example": "1997-12-25",
            "nullable": true
          },
          "first_name": {
            "type": "string",
            "description": "First name.<br />Has a 1 to 50-character limit. Must start with an alphabet and may only contain alphabets, spaces, and apostrophes.",
            "example": "James"
          },
          "middle_name": {
            "type": "string",
            "description": "Middle name.<br />Has a 50-character limit. Must start with an alphabet and may only contain alphabets, spaces, and apostrophes.",
            "example": "Herbert"
          },
          "last_name": {
            "type": "string",
            "description": "Last name.<br />Has a 2 to 50-character limit. Must start with an alphabet and may only contain alphabets, spaces, and apostrophes.",
            "example": "Bond"
          },
          "ssn": {
            "type": "string",
            "description": "Redacted SSN. Format: XXX-XX-9999.",
            "example": "XXX-XX-9999"
          },
          "phone": {
            "type": "string",
            "description": "Numbers only or dash-separated are acceptable",
            "example": "555-111-2222"
          },
          "phone_country_code": {
            "type": "string",
            "description": "Must be a string of 1-3 digits",
            "example": "1"
          },
          "email": {
            "type": "string",
            "description": "Must be a valid email address",
            "example": "james@mi6.gov.uk"
          },
          "addresses": {
            "type": "array",
            "items": {
              "$ref": "#/components/schemas/address"
            }
          },
          "date_created": {
            "type": "string",
            "example": "2021-06-02T13:38:27.965404+00:00",
            "readOnly": true
          }
        },
        "required": [
          "first_name",
          "addresses"
        ]
      },
      "customer-write": {
        "type": "object",
        "x-examples": {
          "example": {
            "brand_person_id": "ac6ee2d3-5a03-4043-a4aa-dda51836b9fd",
            "dob": "1997-12-25",
            "first_name": "James",
            "middle_name": "Herbert",
            "last_name": "Bond",
            "ssn": "XXX-XX-9999",
            "phone": "555-111-2222",
            "phone_country_code": "1",
            "email": "james@mi6.gov.uk",
            "addresses": [
              {
                "address_type": "MAILING",
                "street": "345 California Ave.",
                "street2": "Suite 600",
                "city": "San Francisco",
                "state": "CA",
                "zip_code": "12345-1234",
                "country": "US",
                "is_primary": true
              }
            ]
          }
        },
        "title": "customer-write",
        "properties": {
          "brand_person_id": {
            "type": "string",
            "example": "ac6ee2d3-5a03-4043-a4aa-dda51836b9fd",
            "readOnly": true
          },
          "business_id": {
            "type": "string",
            "example": "null",
            "nullable": true,
            "readOnly": true
          },
          "dob": {
            "type": "string",
            "format": "string",
            "description": "Birthday in YYYY-MM-DD format.",
            "example": "1997-12-25",
            "nullable": true
          },
          "first_name": {
            "type": "string",
            "description": "First name.<br />Has a 1 to 50-character limit. Must start with an alphabet and may only contain alphabets, spaces, and apostrophes.",
            "example": "James"
          },
          "middle_name": {
            "type": "string",
            "description": "Middle name.<br />Has a 50-character limit. Must start with an alphabet and may only contain alphabets, spaces, and apostrophes.",
            "example": "Herbert"
          },
          "last_name": {
            "type": "string",
            "description": "Last name.<br />Has a 2 to 50-character limit. Must start with an alphabet and may only contain alphabets, spaces, and apostrophes.",
            "example": "Bond"
          },
          "ssn": {
            "type": "string",
            "description": "Redacted SSN. Format: XXX-XX-9999.",
            "example": "XXX-XX-9999"
          },
          "phone": {
            "type": "string",
            "description": "Numbers only or dash-separated are acceptable",
            "example": "555-111-2222"
          },
          "phone_country_code": {
            "type": "string",
            "description": "Must be a string of 1-3 digits",
            "example": "1"
          },
          "email": {
            "type": "string",
            "description": "Must be a valid email address",
            "example": "james@mi6.gov.uk"
          },
          "addresses": {
            "type": "array",
            "items": {
              "$ref": "#/components/schemas/address-write"
            }
          }
        },
        "required": [
          "first_name",
          "last_name",
          "addresses"
        ]
      },
      "address": {
        "type": "object",
        "title": "Address",
        "x-examples": {
          "example": {
            "address_id": "5ff2a5f8-2d96-4c89-9edc-ec762ac3844c",
            "address_type": "MAILING",
            "street": "345 California Ave.",
            "street2": "Suite 600",
            "city": "San Francisco",
            "state": "CA",
            "zip_code": "12345-1234",
            "country": "US",
            "is_primary": true,
            "date_created": "2021-10-11T17:54:26.784367+00:00"
          }
        },
        "properties": {
          "address_id": {
            "type": "string",
            "example": "5ff2a5f8-2d96-4c89-9edc-ec762ac3844c",
            "description": "id for address resource",
            "readOnly": true
          },
          "address_type": {
            "type": "string",
            "description": "Address type is one of the following : MAILING, PHYSICAL",
            "enum": [
              "MAILING",
              "PHYSICAL"
            ]
          },
          "street": {
            "type": "string",
            "description": "Has a 1 to 40-character limit. May only contain alphanumerics and the special characters `. , _ - #`",
            "example": "345 California Ave."
          },
          "street2": {
            "type": "string",
            "description": "Has a 40-character limit. May only contain alphanumerics and the special characters `. , _ - #`",
            "example": "Suite 600"
          },
          "city": {
            "type": "string",
            "description": "Has a 2 to 40-character limit. May contain only alphanumerics, `-`, `_`,`.`, and spaces",
            "example": "San Francisco",
            "minLength": 2,
            "maxLength": 40
          },
          "state": {
            "type": "string",
            "description": "Has a 2-character limit for US address.<br />Has a 20-character limit for non US address.",
            "example": "CA"
          },
          "zip_code": {
            "type": "string",
            "description": "zip code in 5-digit (12345) or 9-digit (12345-1234) format for US address.<br />Has a 2 to 20-character limit for non US address.",
            "example": "12345-1234"
          },
          "country": {
            "type": "string",
            "description": "ISO 3166-1 alpha-2 country code.<br />Has a 2-character limit.",
            "example": "US"
          },
          "is_primary": {
            "type": "boolean",
            "description": "Is Primary Address?",
            "example": true
          },
          "date_created": {
            "type": "string",
            "example": "2021-10-11T17:54:26.784367+00:00",
            "description": "Date time address was created",
            "readOnly": true
          }
        },
        "required": [
          "address_type",
          "street",
          "city",
          "state",
          "zip_code",
          "country",
          "is_primary"
        ]
      },
      "address-write": {
        "type": "object",
        "description": "",
        "title": "Address-write",
        "x-examples": {
          "example": {
            "address_type": "MAILING",
            "street": "345 California Ave.",
            "street2": "Suite 600",
            "city": "San Francisco",
            "state": "CA",
            "zip_code": "12345-1234",
            "country": "US",
            "is_primary": true
          }
        },
        "properties": {
          "address_type": {
            "type": "string",
            "description": "Address type is one of the following : `MAILING`, `PHYSICAL`",
            "enum": [
              "MAILING",
              "PHYSICAL"
            ]
          },
          "street": {
            "type": "string",
            "description": "Has a 1 to 40-character limit. May only contain alphanumerics and the special characters `. , _ - #`",
            "example": "345 California Ave."
          },
          "street2": {
            "type": "string",
            "description": "Has a 40-character limit, inclusive. Must start with an alphanumeric, and may only contain alphanumerics and the special characters `. , _ - #`",
            "example": "Suite 600"
          },
          "city": {
            "type": "string",
            "description": "Has a 2 to 40-character limit. May contain only alphanumerics, `-`, `_`,`.`, and spaces",
            "example": "San Francisco",
            "minLength": 2,
            "maxLength": 40
          },
          "state": {
            "type": "string",
            "description": "Has a 2-character limit for US address.<br />Has a 20-character limit for non US address.",
            "example": "CA"
          },
          "zip_code": {
            "type": "string",
            "description": "zip code in 5-digit (12345) or 9-digit (12345-1234) format for US address.<br />Has a 2 to 20-character limit for non US address.",
            "example": "12345-1234"
          },
          "country": {
            "type": "string",
            "description": "ISO 3166-1 alpha-2 country code.<br />Has a 2-character limit.",
            "example": "US"
          },
          "is_primary": {
            "type": "boolean",
            "description": "Is Primary Address?",
            "example": true
          }
        },
        "required": [
          "address_type",
          "street",
          "city",
          "state",
          "zip_code",
          "country",
          "is_primary"
        ]
      }
    }
  },
  "x-readme": {
    "explorer-enabled": true,
    "proxy-enabled": true,
    "samples-enabled": true
  },
  "_id": {
    "buffer": {
      "0": 98,
      "1": 113,
      "2": 147,
      "3": 157,
      "4": 139,
      "5": 109,
      "6": 64,
      "7": 0,
      "8": 75,
      "9": 70,
      "10": 96,
      "11": 240
    }
  }
}
```

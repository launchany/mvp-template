---
layout: swagger
title: Open API example
data: example
permalink: /openapi/example/
consumes:
  - application/json
  - application/xml
produces:
  - application/json
  - application/xml
paths:
  /fruits:
    get:
      summary: List all fruits
      responses:
        200:
          description: An array of fruits
          examples:
            application/json: >
                {
                    "fruits": [
                        {
                            "id": 1,
                            "name": "Cherry",
                            "price": 6.30,
                            "description": "Lovely red cherries",
                            "origin": [
                                "france"
                            ]
                        },
                        {
                            "id": 2,
                            "name": "Peach",
                            "price": 4.10,
                            "origin": [
                                "spain",
                                "italy"
                            ]
                        }
                    ]
                }
            application/xml: >
                <fruits>
                    <fruit>
                        <id>1</id>
                        <name>Tomato</name>
                        <price>2.30</price>
                        <description>A lovely red tomato</description>
                        <origins>
                            <origin>france</origin>
                        </origins>
                    </fruit>
                    <fruit>
                        <id>2</id>
                        <name>Peach</name>
                        <price>5.12</price>
                        <origins>
                            <origin>spain</origin>
                            <origin>italy</origin>
                        </origins>
                    </fruit>
                </fruits>
    post:
      summary: Add a fruit
      parameters:
        - name: name
          in: body
          description: fruit's name
          required: true
        - name: price
          in: body
          type: float
          description: per kilogram fruit's price
          required: true
        - name: description
          in: body
          description: product's description
        - name: origin
          in: body
          description: product's origin
          type: array
          items:
            type: string
          required: true
      responses:
        200:
          description: Product details
          examples:
            application/json: >
                {
                    "id": 1,
                    "name": "Cherry",
                    "price": 6.30,
                    "description": "Lovely red cherries",
                    "origin": [
                        "france"
                    ]
                }
            application/xml: >
                <fruit>
                    <id>1</id>
                    <name>Tomato</name>
                    <price>2.30</price>
                    <description>A lovely red tomato</description>
                    <origins>
                        <origin>france</origin>
                    </origins>
                </fruit>
        401:
            description: Invalid data
            examples:
                application/json: >
                    {
                        "error": "Missing key `price`."
                    }
                application/xml: >
                    <error>
                        <message>Missing key `price`.</message>
                    </error>
        403:
          description: Insufficient right to add a fruit
  /fruits/{id}:
    get:
      summary: Fetch a fruit
      responses:
        200:
          description: Fruit details
          examples:
            application/json: >
                {
                    "id": 1,
                    "name": "Cherry",
                    "price": 6.30,
                    "description": "Lovely red cherries",
                    "origin": [
                        "france"
                    ]
                }
            application/xml: >
                <fruit>
                    <id>1</id>
                    <name>Tomato</name>
                    <price>2.30</price>
                    <description>A lovely red tomato</description>
                    <origins>
                        <origin>france</origin>
                    </origins>
                </fruit>
        404:
            description: Invalid fruit ID
    put:
      summary: Update a fruit
      parameters:
        - name: name
          in: body
          description: fruit's name
          required: true
        - name: price
          in: body
          type: float
          description: per kilogram fruit's price
          required: true
        - name: description
          in: body
          description: product's description
        - name: origin
          in: body
          description: product's origin
          type: array
          items:
            type: string
          required: true
      responses:
        200:
          description: Product details
          examples:
            application/json: >
                {
                    "id": 1,
                    "name": "Cherry",
                    "price": 6.30,
                    "description": "Lovely red cherries",
                    "origin": [
                        "france"
                    ]
                }
            application/xml: >
                <fruit>
                    <id>1</id>
                    <name>Tomato</name>
                    <price>2.30</price>
                    <description>A lovely red tomato</description>
                    <origins>
                        <origin>france</origin>
                    </origins>
                </fruit>
        401:
          description: Invalid data
          examples:
            application/json: >
                {
                    "error": "Price must be a float."
                }
            application/xml: >
                <error>
                    <message>Price must be a float.</message>
                </error>
    patch:
      summary: Partially update a fruit
      parameters:
        - name: name
          in: body
          description: fruit's name
        - name: price
          in: body
          type: float
          description: per kilogram fruit's price
        - name: description
          in: body
          description: product's description
        - name: origin
          in: body
          description: product's origin
          type: array
          items:
            type: string
      responses:
        200:
          description: Product details
          examples:
            application/json: >
                {
                    "id": 1,
                    "name": "Cherry",
                    "price": 6.30,
                    "description": "Lovely red cherries",
                    "origin": [
                        "france"
                    ]
                }
            application/xml: >
                <fruit>
                    <id>1</id>
                    <name>Tomato</name>
                    <price>2.30</price>
                    <description>A lovely red tomato</description>
                    <origins>
                        <origin>france</origin>
                    </origins>
                </fruit>
        401:
          description: Invalid data
          examples:
            application/json: >
                {
                    "error": "Price must be a float."
                }
            application/xml: >
                <error>
                    <message>Price must be a float.</message>
                </error>
    delete:
        summary: Delete a fruit
        responses:
            204:
              description: Product removed
---
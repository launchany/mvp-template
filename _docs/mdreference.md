---
title: Markdown reference example
permalink: /docs/mdreference/
---

[The **Reference** includes all the information users need to know to use your endpoints. That means you'll repeat the information below for each endpoint in your API.

Use this page if you prefer to create Markdown files for your reference. Here's what you'll need to do:
* Delete the OpenAPI reference example file `/_docs/openapi.md`
* Delete the code `<li {% if page.sectionid=='docs' %} class="active" {% endif %}><a href="{{ "/docs/openapi/" | prepend: site.baseurl }}">OpenAPI</a></li>` from the file `/_includes/topnav.html`
* Delete the `- openapi` menu item from the file `/_data/docs.yml`]

### [Retrieve a record]

[The heading above should be a very brief description of what the endpoint does.]

#### HTTP Method and URL

[`GET`, `PUT`, `POST`, or `DELETE` and URL---for example, `GET https://api.payrollrecord.com/timesheet/{employee_id}`]

#### Parameters

[Table that lists all query and path parameters for the endpoint. If this endpoint has query and path parameters, consider listing them in separate tables---one for path parameters, one for query parameters. If there aren't any parameters for this endpoint, replace the table with "None"]

Name | Type | Description | Required?
---- | ---- | ----------- | ---------
[Name or parameter] | [Query or Path] | [Brief description of parameter function. What does it do?] | [Required or Optional]
[Name or parameter] | [Query or Path] | [Brief description of parameter function. What does it do?] | [Required or Optional]
[Name or parameter] | [Query or Path] | [Brief description of parameter function. What does it do?] | [Required or Optional]

#### Example Request

[Code or pseudocode sample of a complete request for this endpoint, including header and body, followed by a table that lists each element in the example request]

Element | Type | Description | Required?
------- | ---- | ----------- | ---------
[Element as it appears in request] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents, including default and valid values] | [Required or Optional]
[Element as it appears in request] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents, including default and valid values] | [Required or Optional]
[Element as it appears in request] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents, including default and valid values] | [Required or Optional]

#### Example Response

[Code or pseudocode sample of a complete response for this endpoint, followed by a table that lists each element in the example response]

Element | Type | Description
------- | ---- | -----------
[Element as it appears in response] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents]
[Element as it appears in response] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents]
[Element as it appears in response] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents]

#### Error and Status Codes

[Table that lists all possible error and status codes for this endpoint]

Code | Message | Meaning
---- | ------- | -------
[HTTP or error code] | [Message for the code, such as "Not Found"] | [Brief description of what the code means within your API, such as "We couldn't complete your request right now"]
[HTTP or error code] | [Message for the code, such as "Not Found"] | [Brief description of what the code means within your API, such as "We couldn't complete your request right now"]
[HTTP or error code] | [Message for the code, such as "Not Found"] | [Brief description of what the code means within your API, such as "We couldn't complete your request right now"]

### [Add an employee]

[The heading above should be a very brief description of what the endpoint does.]

#### HTTP Method and URL

[`GET`, `PUT`, `POST`, or `DELETE` and URL---for example, `POST https://api.payrollrecord.com/employee`]

#### Parameters

[Table that lists all query and path parameters for the endpoint. If this endpoint has query and path parameters, consider listing them in separate tables---one for path parameters, one for query parameters. If there aren't any parameters for this endpoint, replace the table with "None"]

Name | Type | Description | Required?
---- | ---- | ----------- | ---------
[Name or parameter] | [Query or Path] | [Brief description of parameter function. What does it do?] | [Required or Optional]
[Name or parameter] | [Query or Path] | [Brief description of parameter function. What does it do?] | [Required or Optional]
[Name or parameter] | [Query or Path] | [Brief description of parameter function. What does it do?] | [Required or Optional]

#### Example Request

[Code or pseudocode sample of a complete request for this endpoint, including header and body, followed by a table that lists each element in the example request]

Element | Type | Description | Required?
------- | ---- | ----------- | ---------
[Element as it appears in request] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents, including default and valid values] | [Required or Optional]
[Element as it appears in request] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents, including default and valid values] | [Required or Optional]
[Element as it appears in request] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents, including default and valid values] | [Required or Optional]

#### Example Response

[Code or pseudocode sample of a complete response for this endpoint, followed by a table that lists each element in the example response]

Element | Type | Description
------- | ---- | -----------
[Element as it appears in response] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents]
[Element as it appears in response] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents]
[Element as it appears in response] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents]

#### Error and Status Codes

[Table that lists all possible error and status codes for this endpoint]

Code | Message | Meaning
---- | ------- | -------
[HTTP or error code] | [Message for the code, such as "Not Found"] | [Brief description of what the code means within your API, such as "We couldn't complete your request right now"]
[HTTP or error code] | [Message for the code, such as "Not Found"] | [Brief description of what the code means within your API, such as "We couldn't complete your request right now"]
[HTTP or error code] | [Message for the code, such as "Not Found"] | [Brief description of what the code means within your API, such as "We couldn't complete your request right now"]

### [Remove an employee]

[The heading above should be a very brief description of what the endpoint does.]

#### HTTP Method and URL

[`GET`, `PUT`, `POST`, or `DELETE` and URL---for example, `DELETE https://api.payrollrecord.com/employee/{employee_id}`]

#### Parameters

[Table that lists all query and path parameters for the endpoint. If this endpoint has query and path parameters, consider listing them in separate tables---one for path parameters, one for query parameters. If there aren't any parameters for this endpoint, replace the table with "None"]

Name | Type | Description | Required?
---- | ---- | ----------- | ---------
[Name or parameter] | [Query or Path] | [Brief description of parameter function. What does it do?] | [Required or Optional]
[Name or parameter] | [Query or Path] | [Brief description of parameter function. What does it do?] | [Required or Optional]
[Name or parameter] | [Query or Path] | [Brief description of parameter function. What does it do?] | [Required or Optional]

#### Example Request

[Code or pseudocode sample of a complete request for this endpoint, including header and body, followed by a table that lists each element in the example request]

Element | Type | Description | Required?
------- | ---- | ----------- | ---------
[Element as it appears in request] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents, including default and valid values] | [Required or Optional]
[Element as it appears in request] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents, including default and valid values] | [Required or Optional]
[Element as it appears in request] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents, including default and valid values] | [Required or Optional]

#### Example Response

[Code or pseudocode sample of a complete response for this endpoint, followed by a table that lists each element in the example response]

Element | Type | Description
------- | ---- | -----------
[Element as it appears in response] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents]
[Element as it appears in response] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents]
[Element as it appears in response] | [Array, Object, String, Integer, or Float] | [Brief description of what information the element represents]

#### Error and Status Codes

[Table that lists all possible error and status codes for this endpoint]

Code | Message | Meaning
---- | ------- | -------
[HTTP or error code] | [Message for the code, such as "Not Found"] | [Brief description of what the code means within your API, such as "We couldn't complete your request right now"]
[HTTP or error code] | [Message for the code, such as "Not Found"] | [Brief description of what the code means within your API, such as "We couldn't complete your request right now"]
[HTTP or error code] | [Message for the code, such as "Not Found"] | [Brief description of what the code means within your API, such as "We couldn't complete your request right now"]


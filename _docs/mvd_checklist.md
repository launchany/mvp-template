---
title: MVD checklist
permalink: /docs/mvd_checklist/
---

Use this checklist to help you complete your minimum viable API documentation.

Section | Questions to answer | Information to include
------- | ------------------- | ----------------------
Overview | What type of API do you have? | Type of API (RESTful, SOAP, platform-based)
| What can users do with your API? | Brief use cases and examples (2 or 3 sentences)
| Are there any access details or restrictions users need to know about? | Base URL, Rate limits
Authentication | If your API requires an authentication token or key, how do users get one? | Authentication method
| Do tokens/keys expire? | Expiration intervals (if any)
| What should users do if their token/key expires? | Refreshing expired tokens/keys
| How do users pass authentication to your API? | Example authorization header
Workflows | What is the optimal/assumed workflow for the 2 or 3 most useful things users can do with your API? | Link to the reference for each endpoint mentioned in the workflow
Code samples | What does the code look like for common use cases? | Complete code samples and code snippets that users can copy and paste
Reference | What do users need to know to use each endpoint? | For each endpoint:
| | HTTP method (GET, PUT, POST, DELETE)
| | Complete request URL
| | Parameters (path and query): name, type, description, and whether the parameter is requred
| | Example request (including header and body)
| | List of each element in the example request, including the type, description, and whether the element is required
| | Example response
| | List of each element in the example response, including type and description
| | List of error and status codes, including the code, message, and meaning

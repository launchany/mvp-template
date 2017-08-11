---
title: Get started
permalink: /docs/home/
redirect_from: /docs/index.html
---

**Welcome to the documentation for [name of API]!**

[Name of API] is a [type - RESTful, SOAP, platform-based] API that you can use to:

* [Brief example use case - 1 sentence]
* [Brief example use case - 1 sentence]
* [Brief example use case - 1 sentence]

[Name of API] uses [protocol for requests, such as HTTP protocols `GET`, `POST`, `PUT`, and `DELETE`]. Responses are returned in [language] format. [Other items to mention about requests and responses, if applicable: whether users can specify the response language using the `ACCEPT` header.]

To access [name of API], you'll need [describe access requirements, which might include an account with your product, an authentication token, username/password, or other credentials].

The base URL is [your API's base URL]. Each user is limited to [number] requests per second. If you exceed this rate limit, [explain what happens if rate limit is exceeded---for example, will users see an error response?].

## Authentication

[Details in this section will vary based on your authentication method, but make sure to explain these things:

* If your API requires an authentication token or key, how do users get one?
* If authentication tokens or keys expire, what's the expiration interval? How do users refresh expired tokens or keys?
* How do users pass authentication information to your API? For example, do they use an Authorization header?

The prompts in this section assume that users will need an authentication token and the token should be kept private.]

You'll need to include an [authentication token] with all of your requests to [name of API]. Anyone with your [authentication token] can access your data through our API, so keep your [authentication token] private. Don't share it with other users, and make sure to remove it from any code samples.

To get your [authentication token], [explain how to get the token---for example, contact Customer Support, send a call with your username and password to the API, or go to your account at our website].

[Authentication tokens] expire [list expiration interval - for example, every 2 weeks or after 1 year]. If your [authentication token] expires, [explain how to refresh - for example, contact Customer Support or go to your customer account and click "Refresh Token"].

To pass your authentication information with your API requests, [explain how to pass authentication token---for example, use the authorization header in cURL].

---
title: OpenAPI reference example
permalink: /docs/openapi/
---

[Use this page if you prefer to use [Swagger UI](https://github.com/swagger-api/swagger-ui) to render your reference documentation instead of creating Markdown files.

Here's what you'll need to do:
* Replace the file `/dist/swagger_petstore.yml` with your own YAML file in your local copy of the template repo to display your spec in the iframe below
* Delete the Markdown reference example file `/_docs/mdreference.md`
* Delete the code `<li {% if page.sectionid=='docs' %} class="active" {% endif %}><a href="{{ "/docs/mdreference/" | prepend: site.baseurl }}">Reference</a></li>` from the file `/_includes/topnav.html`
* Delete the `- mdreference` menu item from the file `/_data/docs.yml`

To change formatting for the iframe, edit the `.intrinsic-container` and `.intrinsic-container iframe` classes in the file `/_sass/bootstrap/_grid.scss`.

The example spec used here is based on the [petstore-expanded.json](https://github.com/OAI/OpenAPI-Specification/blob/master/examples/v2.0/json/petstore-expanded.json) example from the [OpenAPI Specification Repository](https://github.com/OAI/OpenAPI-Specification).]

<div class="intrinsic-container">

	<iframe src="/mvd-template/dist/"></iframe>

</div>

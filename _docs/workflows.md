---
title: Workflows
permalink: /docs/workflows/
---

[Describe the optimal or assumed workflows for a few things users can accomplish with your API. Think about the most common and highest-impact outcomes. Each workflow should walk users through a brief explanation, any prerequisites, and the steps involved in completing the outcome with your API, including the reasons users must take each step and the API call required to finish the step.

Here's an example workflow for an API that allows you to retrieve and update timesheet records.

### Add a description to explain overtime on employee's timesheet

You asked an employee, Meghan, to work 2 hours of overtime last Thursday. To make sure Payroll approves Meghan's timesheet with the extra 2 hours, you need to add a description.

To complete this outcome, you need Meghan's employee ID number and your authentication token for the API.

1. Retrieve the record for Meghan's timesheet for last Thursday. Send a request to the `GET` https://api.payrollrecord.com/timesheet endpoint. Your request must include Meghan's employee ID number and the date as query parameters. Here's the complete request in cURL:

	```
	curl --request GET \
	  --url 'https://api.payrollrecord.com/timesheet?employee={employee ID number}&date=2017-05-25' \
	  --header 'authorization: {your authentication token}'
	```

2. The JSON object in the response will include a unique ID for the timesheet for last Thursday, `timesheet_ID`. Note this ID---you will use it in the next request.

3. Send a request to the `PUT` https://api.payrollrecord.com/timesheet endpoint. Your request must include the `timesheet_ID` as a query parameter and the description you want to add in the request body. Here's the complete request in cURL:

	```
	curl --request PUT \
	  --url 'https://api.payrollrecord.com/timesheet?timesheet_id={timesheet ID number}' \
	  --header 'authorization: {your authentication token}' \
	  --header 'content-type: multipart/form-data; boundary=----WebKitFormBoundary7MA4YWxkTrZu0gW' \
	  --form 'description=Employee worked 2 hours of overtime to complete data entry. Overtime approved by {your name}.'
	```

Now, if you send another request for Meghan's timesheet for May 25, 2017 (like you did in Step 1), you will see the description you added at the end of the JSON object in the response.]


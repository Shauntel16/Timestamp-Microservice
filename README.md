Timestamp Microservice Description
This app is a simple full-stack JavaScript microservice that provides timestamp conversion functionality. It accepts a date string or a Unix timestamp as input via a URL parameter and returns a JSON response with both the Unix timestamp and the UTC string representation of that date.

The microservice supports:

Parsing valid date strings (in GMT, ignoring time zones).

Parsing valid Unix timestamps.

Handling invalid dates with an error response.

Returning a consistent JSON object with both date formats.

This project was built to fulfill the FreeCodeCamp Timestamp Microservice challenge and can be deployed locally or to any site builder platform. It demonstrates backend date parsing, API response formatting, and error handling using Node.js and Express.

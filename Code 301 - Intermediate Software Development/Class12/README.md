100’s = Informational status codes that indicate the server has received the request and is continuing the process.
200’s = Success status codes that indicate the request has been successfully received, understood, and processed by the server.
300’s = Redirection status codes that indicate further action is needed by the client to complete the request, often involving redirection to a different URL.
400’s = Client Error status codes that indicate an error in the client's request, such as invalid syntax, authentication failure, or insufficient permissions.
500’s = Server Error status codes that indicate an error on the server side while processing the request, such as internal server issues or unhandled exceptions.
What is a status code 202?

Status code 202 is "Accepted," indicating that the request has been accepted for processing but is not yet completed.
What is a status code 308?

Status code 308 is "Permanent Redirect," indicating that the requested resource has been permanently moved to a different URL.
What code would you use if an update didn’t return data to a client?

If an update didn't return data to a client, you would use the status code 204 "No Content" to indicate a successful request without any response body.
What code would you use if a resource used to exist but no longer does?

If a resource used to exist but no longer does, you would use the status code 410 "Gone" to indicate that the resource is permanently gone and will not be available again.
What is the 'Forbidden' status code?

The 'Forbidden' status code is 403, indicating that the server understood the request but refuses to authorize it due to insufficient permissions.
Why do we need to pull our MongoDB database string out of our server and put it into our .env?

We need to put the MongoDB database string in the .env file to separate configuration from code and keep sensitive information secure.
What is middleware?

Middleware refers to software components or functions that sit between the client and the server to handle requests and responses, adding functionality to the application.
What does app.use(express.json()) do?

app.use(express.json()) is middleware that allows the application to parse JSON data sent in the request body and make it available in the req.body object.
What does the /:id mean in a route?

The /:id in a route represents a route parameter, allowing dynamic matching of URLs with different values, which can be accessed in the request handler using req.params.id.
What is the difference between PUT and PATCH?

PUT is used to completely replace a resource, while PATCH is used to partially update a resource, modifying only the specified fields.
How do you make a default value in a schema?

In a schema, you can set a default value for a field by specifying a default property in the field definition, assigning it the desired default value.
What does a 500 error status code mean?

A 500 error status code, specifically 500 Internal Server Error, indicates that an unexpected condition occurred on the server, resulting in the inability to fulfill the request.
What is the difference between a status 200 and a status 201?

Status code 200 "OK" indicates a successful request, while status code 201 "Created" specifically indicates that a new resource has been successfully created as a result of the request.

## Things I want to know more about
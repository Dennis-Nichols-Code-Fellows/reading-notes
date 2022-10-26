# Code 301 - Class 8 notes

## [REST APIs](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

1. What does REST stand for?
Representational State Transfer

2. REST APIs are designed around a ____.
REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client.

3. What is an identifier of a resource? Give an example.
Something that uniquely identifies that resource. E.g. a web address: https://maps.google.com

4. What are the most common HTTP verbs?
GET, POST, PUT, PATCH, and DELETE

5. What should the URIs be based on?
When possible, resource URIs should be based on nouns (the resource).

6. Give an example of a good URI.
canvas.instructure.com/courses

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
An API that requires many requests to deliver desired resources - a bad thing for the load it causes on the server.

8. What status code does a successful GET request return?
200

9. What status code does an unsuccessful GET request return?
404

10. What status code does a successful POST request return?
201

11. What status code does a successful DELETE request return?
204

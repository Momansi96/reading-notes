# Class13  

[Return to home page](https://momansi96.github.io/reading-notes/). 


## Status Codes 


* In your own words, describe what each group of status code represents:

 100’s = they tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client.

 200’s = They tell the client that its request was accepted. 

 300’s = They tell the client that the resource they are requesting isn’t available at the expected location anymore. 

 400’s = They are all about invalid requests a client sent to a server. 

 500’s = they indicate problems with overwhelmed servers or unreachable servers behind proxies. 


* What is a status code 202?

 the request has met all validation requirements at the time of sending.


* What is a status code 308?

This tells the client to use another URL to access the resource and not use the current URL anymore. 

* What code would you use if an update didn’t return data to a client?

204 No Content. 

* What code would you use if a resource used to exist but no longer does?

410 Gone. 

* What is the ‘Forbidden’ status code?

403 Forbidden. 


## Rest API 


* Why do we need to pull our MongoDB database string out of our server and put it into our .env?

If you are running MongoDB locally and have not enabled authentication, your MongoDB instance is not secure. 

* What is middleware?

Middleware is software which lies between an operating system and the applications running on it.

* What does app.use(express.json()) do?

it is a method inbuilt in express to recognize the incoming Request Object as a JSON Object.

* What does the /:id mean in a route?

it's a dynamic route. 

* What is the difference beween PUT and PATCH?

that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource. 

* How do you make a defalut value in a schema?

You can use setDefaultsOnInsert. 

* What does a 500 error status code mean?

this indicates the server cannot find a better 5xx error code to response. 

* What is the difference between a status 200 and a status 201?

The HTTP 200 OK success status response code indicates that the request has succeeded, The HTTP 201 Created success status response code indicates that the request has succeeded and has led to the creation of a resource. 


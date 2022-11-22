# CRUD

> ## Status Codes Based On REST Methods

* CRUD = (Create, Read, Update, Delete)

1. In your own words, describe what each group of status code represents:

100’s = information code to tell the client his request will fail before sending the body

200’s = success code. code mets all validation requirements at the time of sending

300’s = redirection codes. Tells the user the info is no longer at this address and must enter a new location.

400’s = client error codes. They are invalid requests a client sent to a server

500’s = Server error codes. Something wrong behind the scenes like with the server.

2. What is a status code 202?
   * Accepted

3. What is a status code 308?
   * Permanent Redirect 

4. What code would you use if an update didn’t return data to a client?
   * 204 - No content

5. What code would you use if a resource used to exist but no longer does?
   * 410

6. What is the ‘Forbidden’ status code?
   * 403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

References:
[Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

> ## Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
   * When we deploy our server. We want to use something other than our local host. However it is hard coded in our server than thats the one we will always use.

2. What is middleware?
   * code that runs when the server gets a request but before it gets pasted to our routes.

3. What does app.use(express.json()) do?
   * let our server accept json as a body.

4. What does the /:id mean in a route?
   * its a parameter.

5. What is the difference between PUT and PATCH?
   * Patch only updates what the user passes. Put will update all the information at once.

6. How do you make a default value in a schema?
   * just type 'default: '

7. What does a 500 error status code mean?
   * error on the server side.

8. What is the difference between a status 200 and a status 201?
   * 201 means successfully created an object. While 200 means everything was successful. 201 is a more created way of telling the user they created something.

References:
[Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

[Return home](../README.md)

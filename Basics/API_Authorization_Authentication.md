##  🚔 Basics of API, Authorization, Authentication and Integration

#### API

A Representational State Transfer (REST) API is an architectural style for an application program interface (API) that uses HTTP requests to access and use data. That data can be used to GET, PUT, POST and DELETE data types, which refers to the reading, updating, creating and deleting of operations concerning resources. REST was initially created as a guideline to manage communication on a complex network like the internet.


```
GET - View
PUT - Update
POST - Create
DELETE - delete
```


Status Codes
```
1XX - Informational
    Request received / processing
2XX - Success
    Successful received, understood, accepted
3XX - Redirect
    Further action needs to be taken in order to complete the request
4XX - Client Error
    Request contains bad syntax or cannot be fulfilled
5XX - Server Error
    Server failed to fulfill an apparently valid request
```

200 - OK
201 - OK Created
301 - Moved to new URL
304 - Not Modified
400 - Bad Request
401 - Unauthorized
403 - Forbidden
404 - Not Found
500 - Internal Server Error

API Key, Client Code, Client Secret, OAuth Client Id



#### Authentication 
https://www.techtarget.com/searchsecurity/definition/authentication


#### Authorization
https://auth0.com/intro-to-iam/what-is-authorization
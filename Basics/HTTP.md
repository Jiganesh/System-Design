# :love_letter: HTTP

##### HTTP
HyperText Transfer Protocol (HTTP) is the core communications protocol which is used to access the World Wide Web and is used by all of today’s all kind of applications.

Communication between webserverrs and clients
Loading Pages, Form Submit, AJAX calls

Protocol: set of rules

HTTP uses a message-based model which works by sending and receiving HTTP messages by the client and the server.
HTTP messages are of two types:
1. Request
2. Response

HTTP request is sent by the client to the server to which the server responds by sending HTTP response.

HTTP request contain:

• HTTP version
• Method: specifies the action that the client is requesting (GET, PUT, POST, DELETE)
• URL: specifies the resource that the client is requesting. 
• Headers: contain additional information about the request.
• Body: may contain data.

HTTP response contain:

• HTTP version
• Status code and it's brief description
• Headers
• Body

HTTPS is stateless
Every request is completely independent of other requests (doesnt remember previous requests)
Programming, Local Storage, Cookies, Session are used to create enhanced user experience


##### HTTPS 

Hyper Text Transfer Protocol Secure
Data sent is encrypted
SSL / TLS
Install certificate on web host


HTTP Methods:
GET - Retrieves data from the server
POST - Sends data to the server
PUT - Updates data on the server
DELETE - Deletes data from the server

HTTP Header Fields
Request Header Fields
```
Accept-xxx
cookies
content-type
content-length
authorization
user-agent
referer
```
Response Header Fields
```
Server
set-cookie - send cookies to the client
content-type
content-length
date

```
General Header Fields
```
Request URL
Request Method
Status Code
Remote Address
Referrer Policy
```

##### HTTP/2

Major revision of HTTP
Faster, more efficient, more secure
Response multiplexing
Reduce latency by enabling full request and response multiplexing


[HTTP request and response](https://www.youtube.com/watch?v=iYM2zFP3Zn0)

 
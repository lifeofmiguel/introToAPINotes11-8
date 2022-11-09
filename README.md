# introToAPINotes11-8

A server is like a big computer it has all the same parts 
as the laptop you use for work, it’s just faster and more powerful
"http" tells the browser to
use the rules of HTTP when talking with the server
GET - Asks the server to retrieve a resource
PUT - Asks the server to edit/update an existing resource
DELETE - Asks the server to delete a resource
POST - Asks the server to create a new resource
Logging-in with a username and password is one example of a technical
process known as authentication there are several techniques APIs use 
to authenticate called authentication schemes.
the official name for it is Basic Authentication "Basic Auth"

Authentication: process of the client proving its identity to the
server
Credentials: secret pieces of info used to prove the client's
identity (username, password...) 

There are currently two versions of OAuth, aptly named OAuth 1 and
OAuth 2
<---------OAuth2--------->
 • The User - A person who wants to connect two websites they use
 
 • The Client - The website that will be granted access to the user's data
 
 • The Server - The website that has the user's data 
 
 Step 1 - User Tells Client to Connect to Server 
 Step 2 - Client Directs User to Server
 Step 3 - User Logs-in to Server and Grants Client Access 
 Step 4 - Server Sends User Back to Client, Along with Code 
 Step 5 - Client Exchanges Code + Secret Key for Access Token 
 Step 6 - Client Fetches Data from Server 
 <--------OAuth1--------->
  access tokens do not expire
  OAuth 1 includes an extra step. Between
Steps 1 and 2 above, OAuth 1 requires the client to ask the server for a
request token. A third difference is that OAuth 1 requires requests to be digitally
signed

 • OAuth: an authentication scheme that automates the key
exchange between client and server.
 • Access Token: a secret that the client obtains upon successfully
completing the OAuth process.
 • Scope: permissions that determine what access the client has to
user's data. 

Sending a GET request to /orders and receiving all three
million orders would not be very helpful REST has a way 
for searching through data.

 • SOAP: API architecture known for standardized message formats 
 • REST: API architecture that centers around manipulating
resources
 • Resource: API term for a business noun like customer or order
 • Endpoint: A URL that makes up part of an API. In REST, each
resource gets its own endpoints
 • Query String: A portion of the URL that is used to pass data to the
server
 • Query Parameters: A key-value pair found in the query string
(topping=cheese)
 • Pagination: Process of splitting up results into manageable
chunks 

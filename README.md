# insecure-cookie-flags
Tool for esting insecure cookie flags
# Script description
As HTTP is a stateless protocol,
cookies provide a way to store persistent data on the client side. This allows a web server to
have session management by persisting data to the cookie for the length of the session.
Cookies are set from the web server in the HTTP response using a Set-Cookie header. They
are then sent back to the server through the Cookie header. This recipe will look at ways to
audit the cookies being set by a website to verify if they have secure attributes or not.

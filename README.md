# spring-boot-docker
bash-3.2$ cf ic -v init

REQUEST: [2016-12-21T11:58:47-05:00]
POST /UAALoginServerWAR/oauth/token HTTP/1.1
Host: login.ng.bluemix.net
Accept: application/json
Authorization: [PRIVATE DATA HIDDEN]
Connection: close
Content-Type: application/x-www-form-urlencoded
User-Agent: go-cli 6.22.2+a95e24c / darwin

grant_type=refresh_token&refresh_token=eyJhbGciOiJIUzI1NiJ9.eyJqdGkiOiIzODgxMjI1Yi0yZDI5LTRkYmMtOWVkYi1mOTI5N2QzMjJhYmEtciIsInN1YiI6ImY5MzAyMzQ0LTYxNjctNDE1Yi1hMDQ1LWU0ZDBkMTAyNzM4ZSIsInNjb3BlIjpbIm9wZW5pZCIsInVhYS51c2VyIiwiY2xvdWRfY29udHJvbGxlci5yZWFkIiwicGFzc3dvcmQud3JpdGUiLCJjbG91ZF9jb250cm9sbGVyLndyaXRlIl0sImlhdCI6MTQ4MjMzNzE5MywiZXhwIjoxNDg0OTI5MTkzLCJjaWQiOiJjZiIsImNsaWVudF9pZCI6ImNmIiwiaXNzIjoiaHR0cHM6Ly91YWEubmcuYmx1ZW1peC5uZXQvb2F1dGgvdG9rZW4iLCJ6aWQiOiJ1YWEiLCJncmFudF90eXBlIjoicGFzc3dvcmQiLCJ1c2VyX25hbWUiOiJBdmFuY2hhYTFAYWV0bmEuY29tIiwib3JpZ2luIjoidWFhIiwidXNlcl9pZCI6ImY5MzAyMzQ0LTYxNjctNDE1Yi1hMDQ1LWU0ZDBkMTAyNzM4ZSIsInJldl9zaWciOiI0NTcxY2E4ZiIsImF1ZCI6WyJjZiIsIm9wZW5pZCIsInVhYSIsImNsb3VkX2NvbnRyb2xsZXIiLCJwYXNzd29yZCJdfQ.GV67f2ddFyaGrNGAymCq-Nz-ObUOPjhwsgYaK4F563c&scope=

RESPONSE: [2016-12-21T11:58:48-05:00]
HTTP/1.1 200 OK
Connection: close
Transfer-Encoding: chunked
Cache-Control: no-cache, no-store, max-age=0, must-revalidate,no-store
Content-Security-Policy: default-src 'self' www.ibm.com 'unsafe-inline';
Content-Type: application/json;charset=UTF-8
Date: Wed, 21 Dec 2016 16:58:47 GMT
Expires: 0
Pragma: no-cache,no-cache
Server: Apache-Coyote/1.1
Strict-Transport-Security: max-age=2592000 ; includeSubDomains
X-Backside-Transport: OK OK,OK OK
X-Content-Type-Options: nosniff
X-Frame-Options: DENY
X-Global-Transaction-Id: 472403215
X-Powered-By: Servlet/3.1
X-Xss-Protection: 1; mode=block

6de
{"access_token":"[PRIVATE DATA HIDDEN]","token_type":"[PRIVATE DATA HIDDEN]","refresh_token":"[PRIVATE DATA HIDDEN]","expires_in":1209600,"scope":"cloud_controller.read password.write cloud_controller.write openid uaa.user","jti":"148fb551-2613-42a8-83a2-789b22cd63c8"}
0


Deleting old configuration file...
Generating client certificates for IBM Containers...
Storing client certificates in /Users/a213129/.ice/certs/...

Storing client certificates in /Users/a213129/.ice/certs/containers-api.ng.bluemix.net/6535e67d-f9aa-419a-9330-c87b901268ad...
Client ID:              e8ecacb0-6802-4937-8bdc-55c2bc37b071
Client Secret:     qU0wO2tI3iG3xO6kW4kQ2nP8lX1fX2lW0oJ2rW3kX2eP6iO5iK
Authorize URL:

https://apicm.aetna.com/healthcare/prod/v3/auth/oauth2/authorize

 

Token URL:

 

https://apicm.aetna.com/healthcare/prod/v3/auth/oauth2/token
OK
The client certificates were retrieved.

Checking local Docker configuration...
OK

Authenticating with the IBM Containers registry host registry.ng.bluemix.net...
FAILED
The attempt to authenticate with the IBM Containers registry host registry.ng.bluemix.net was unsuccessful.
****Flag --email has been deprecated, will be removed in 1.13.
Error response from daemon: Get https://registry.ng.bluemix.net/v1/users/: EOF


When you are not connected to the IBM Containers registry host, you can run only a limited number of IBM Containers commands. Check the spelling of the host URL and try again. If the host URL is correct, open a new command line or terminal window before retrying.

Dec 21 12:14:12 MA213129A-HFD Docker[607]: Socket.TCPV4.read tcp:198.23.117.106:443: caught Uwt.Uwt_error(Uwt.ECONNRESET, "uwt_read", "") returning Eof
Dec 21 12:14:12 MA213129A-HFD Docker[607]: PPP.listen callback caught Uwt.Uwt_error(Uwt.ENOTCONN, "shutdown", "")
Dec 21 12:14:12 MA213129A-HFD Docker[607]: Socket.TCPV4.read tcp:198.23.117.106:443: caught Uwt.Uwt_error(Uwt.ECONNRESET, "uwt_read", "") returning Eof


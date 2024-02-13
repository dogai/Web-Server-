The fundamentals of socket programming for TCP connections in Python are explored. The creation of a socket,
binding to a specific address and port, and handling of HTTP packets—sending and receiving them—are covered.
Additionally, the basics of HTTP header format are grasped.

The task involves the development of a web server capable of handling one HTTP request at a time. The incoming HTTP 
request is accepted and parsed, the requested file is retrieved from the server’s file system, and an HTTP response 
message with the requested file preceded by header lines is constructed. The response is then transmitted directly to
the client. If the requested file is unavailable on the server, an HTTP “404 Not Found” message is promptly sent back
to the client.

Uploaded files contain:
    - Python code for the Web Server,
    - HelloWorld.html file for running the server, and
    - Report containing the explanation every step of the assignment.

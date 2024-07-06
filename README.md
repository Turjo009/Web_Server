# Web_Server
I built a web server using C language. It can connect to multiple clients at the same time using TCP and send and recieve HTTP requests.

# Program:
http server
# Purpose:
allocate a socket and then repeatedly execute the following:
1. wait for the next connection from a client
2. read http request, reply to http request
3. close the connection
4. go back to step (1)

# Syntax:
http_server [ port ]
port  - protocol port number to use

## Note:
The port argument is optional. If no port is specified, the server uses the port specified in config.h

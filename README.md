# grpc

## type of grpc communication

* Unary RPC

Client sends one request, then server reply one response

* Server streaming RPC

Client sends one reqest, then server reply multiple responses. And after responsing, server can send response to client, when server status is changed.

* Client streaming RPC

Client sends multiple request, then server reply one response after it receive all requests.

* Bidirectional streaming RPC

When a client sends a request, the server and client establish a connection and can send requests and responses to each other at any time.
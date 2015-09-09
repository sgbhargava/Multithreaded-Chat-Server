# Multithreaded-Chat-Server
This project demonstrates a multithreaded chat server and client. The server starts a new thread for every client
that connects to it. Every client has two threads, one to listen to the server and one more to wait for the user 
to input commands.

The objectives of the client server implementation were:
1.
Create a server which will allow multiple people to have a discussion online.
2.
The server should spin a thread to service every new client.
3.
Client address book is shared among all client threads on the server and it has to be protected using a mutex lock.
4.
Create a client program which will talk to the server and run on the client machine.
5.
The client program should provide an interface between the client user and the server.


<h2> Hi folks, here we have a code of client-server application, this way i'm describe the steps to run in your machine: </h2>

<h3> How to run:</h3>

* Setup: Linux Machine, GCC installed and text editor that supported language C sintax *
(OK setup? So, lets go)


1⁰ step, run MakeFile:
With the program open, put on your terminal the command make, to build the instructions for the computer run code in C.

<b> terminal: make </b>

2⁰ step, run the Server:
The server needs be the firt part of code to build  with named the comunication (v4 or v6) and the socket port that you wanna be connected.

<b> terminal: ./server v4 51511 </b> 

3⁰ step, connect a Client:
Therefore, now we need to connect a client at this server. For this, just to run a client code with the type of communication and sock port of it.

<b> terminal: ./client 127.0.0.1 51511 </b>

*So, now we have a connection with client and server. You can order to services to server and estamblish a communications.*  

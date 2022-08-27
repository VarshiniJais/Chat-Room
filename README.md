# Chat-Room
In this project, we will be implementing chat room using socket programming 
in Python. Sockets are endpoints for a communication channel. Socket is setup 
for each end and chat room is set up for different clients through the server. 
This project uses client-server architecture in which multiple clients can 
connect to the same server through multi-threading and communicate with 
each other. The server, apart from facilitating TCP connection to clients, keeps 
a record of the clients joining the connection and the clients terminating the 
connection. The clients can choose to join the connection or terminate the 
connection by typing ‘exit’. Once the TCP connection has been established, the 
clients can start communicating with each other, which is broadcasted to all 
the clients in the network

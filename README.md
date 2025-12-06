NU-Information Exchange System

This is a C++ implementation of a multi-campus communication system for FAST-NUCES campuses.
It uses TCP for reliable messaging and UDP for status updates and broadcasts.

Files:
- `server.cpp` – Central Server handling client connections, authentication, message routing, and admin broadcasts.  
- `client.cpp` – Campus Client connecting to the server, sending/receiving messages, and sending periodic heartbeats.

How to Run:
- WE used vmware and ubunto for this project.
- First made files with name server.cpp and client.cpp.
- The commands are under on how to run them 

1. Server
g++ server.cpp -o server -pthread
./server

2. Client
g++ client.cpp -o client -pthread
./client

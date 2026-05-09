# Java Multithread Chat — Sockets

A client-server chat application built in Java using sockets and multithreading.
Each client connection is handled in a separate thread, allowing multiple users
to connect and communicate simultaneously.

## How it works

- **Server**: listens for incoming connections and spawns a new thread per client
- **Client**: connects to the server and sends/receives messages in real time
- Communication is handled through Java Sockets (java.net)

## Technologies

- Java
- Sockets (java.net.Socket / ServerSocket)
- Multithreading (java.lang.Thread)

## How to run

1. Run the `Servidor` project first
2. Run one or more instances of the `Client` project
3. Clients can now send messages through the server

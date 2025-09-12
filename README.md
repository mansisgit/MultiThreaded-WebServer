# MultiThreaded-WebServer
This is Networking and Advanced Java combination Project 


# Multithreaded Web Server

A lightweight **multithreaded web server** built from scratch in **Java**, designed to handle multiple client requests concurrently using **socket programming** and **thread pools**.  
This project demonstrates how a basic HTTP server works internally from accepting connections to parsing requests and sending responses  while showcasing the power of concurrency in backend development.

---

## Features

- **Concurrent Request Handling** – Uses multithreading to serve multiple clients simultaneously.
- **Socket Programming** – Implements server-client communication over TCP.
- **Thread Pool** – Efficiently manages worker threads to reduce thread creation overhead.
- **HTTP Request Parsing** – Reads and interprets raw HTTP request lines and headers.
- **Static File Serving** – Responds with requested files from the server's root directory.
- **Graceful Shutdown** – Closes all sockets and threads safely on exit.

---

## Tech Stack

| Component            | Technology Used |
|----------------------|----------------|
| Language             | Java |
| Networking           | Java Sockets (ServerSocket, Socket) |
| Concurrency          | Java Threads, Thread Pools (ExecutorService) |
| Protocol             | HTTP/1.0 & HTTP/1.1 basics |
| I/O Handling         | InputStream, OutputStream |

---



# Run the server (default port 8080)
java -cp bin com.example.Server

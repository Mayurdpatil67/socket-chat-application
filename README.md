# Socket Chat Application

This project is a simple client-server chat application implemented in Java using sockets. The application facilitates two-way communication between a client and a server over a network.

---

## Features
- Real-time text-based messaging between client and server.
- Utilizes `Socket` and `ServerSocket` classes for connection and communication.
- Easy-to-understand implementation for educational purposes.
- Graceful termination of connections.

---

## Prerequisites
- Java Development Kit (JDK) installed.
- Basic understanding of Java programming and networking concepts.

---

## How It Works
1. **Server**:
   - Starts by listening on a specific port (port `2100` in this case).
   - Accepts incoming connections from a client.
   - Reads messages sent by the client and allows the server user to respond.
   
2. **Client**:
   - Connects to the server using the specified IP address (`localhost` in this case) and port (`2100`).
   - Sends messages to the server and displays the responses received.

3. Communication continues until the client sends the message `end`, which terminates the chat session.

---

## Files
1. `Client.java` - The client-side implementation.
2. `Server.java` - The server-side implementation.

---

## How to Run the Application

1. **Compile the Code**:
   Open a terminal and navigate to the directory containing the code files. Compile both files using the following commands:
   ```bash
   javac Client.java
   javac Server.java

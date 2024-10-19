# WebSocket

WebSocket is a protocol that provides full-duplex communication channels over a single TCP connection. This allows messages to be sent back and forth between the client and the server simultaneously. It is more efficient than traditional HTTP polling for real-time applications.

## Key Features:

### Full-Duplex Communication: 

Both client and server can send and receive messages independently.

### Persistent Connection: 

A single WebSocket connection is established and maintained, allowing for low-latency communication.

### Reduced Overhead: 

Since it only requires one connection to be established, WebSocket reduces the overhead of opening multiple HTTP connections.

### How it works:

The client sends an HTTP request to initiate a WebSocket connection (via a handshake).

Once the connection is established, the communication protocol switches to WebSocket.

Both parties can then send and receive messages through this persistent connection.

WebSockets are ideal for applications that require constant updates or two-way communication, like:

- Chat applications
- Live updates (e.g., stock tickers)
- Online multiplayer games
- Collaboration tools (e.g., Google Docs)

https://socket.io/
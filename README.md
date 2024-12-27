# Python Socket Client-Server Communication

This project demonstrates a simple client-server communication system using Python's `socket` and `threading` modules. The server can handle multiple clients at once by creating separate threads for each connection. The client can send messages to the server, and the server prints the received messages.

## Features

- **Multithreaded server**: Handles multiple clients simultaneously using Python's threading module.
- **Message communication**: Client sends messages to the server, which are displayed on the server console.
- **Disconnect functionality**: Clients can disconnect from the server by sending a special message `!DISCONNECT`.

## Requirements

- Python 3.x
- No external libraries are required (only standard libraries: `socket`, `threading`).

## Setup Instructions

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/your-repository-name.git
cd your-repository-name

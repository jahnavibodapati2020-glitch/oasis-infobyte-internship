# Chat Application (Client-Server)
## Overview
This project is a simple command-line chat application developed using Python and socket programming. It enables real-time communication between a client and a server over a network.

## Key Features
- Real-time bidirectional communication
- Client-server architecture using TCP sockets
- Dynamic server connection via IP address input
- Basic error handling for connection failures
- Graceful termination using exit command

## Technologies
- Python 3
- Socket Programming (TCP/IP Networking)

## Project Structure
ChatApp/
│── server.py
│── client.py

## Installation
1. Clone the repository:
git clone <repository-url>
cd ChatApp
2. Ensure Python 3 is installed:
python --version

## Execution
### Step 1: Start Server
python server.py

### Step 2: Start Client
(Open a new terminal)
python client.py

### Step 3: Connect to Server
Enter the server IP address when prompted:
- Localhost: `127.0.0.1`
- Network: `192.168.x.x`

## Usage
- Enter messages in the terminal to communicate
- Messages are transmitted instantly between client and server
- Type `exit` to terminate the session

## Concepts Demonstrated
- Socket creation and binding
- Client-server communication model
- Data encoding and decoding
- Network programming fundamentals

## Future Enhancements
- Graphical User Interface (GUI) using Tkinter
- Multi-client support with threading
- Message persistence (chat history)
- File and multimedia sharing
- End-to-end encryption

## Author
Jahnavi Bodapati

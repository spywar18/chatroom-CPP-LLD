# 🧵 chatRoomCpp

A simple multithreaded chat room application built in C++ using Boost.Asio for asynchronous network communication.

---

## 🚀 Features

- Asynchronous I/O with Boost.Asio  
- Multithreading for handling multiple clients  
- Basic chat room with message broadcast  
- Clean modular design with `Session`, `Room`, and `Message` components

---

## 🧠 Architecture

- **Session** – Handles communication with each connected client  
- **Room** – Manages connected sessions and message delivery  
- **Message** – Encodes and decodes message content  
- **Server** – Accepts new connections and starts sessions  
- **Client** – Connects to server and sends/receives messages

---

## 🛠️ Build Instructions

```bash
# Clone the repository
git clone https://github.com/your-username/chatRoomCpp.git
cd chatRoomCpp

# Build the project
make
💻 Run the Server
bash
Copy
Edit
./chatApp <port>
# Example:
./chatApp 8080
💬 Run the Client
bash
Copy
Edit
./clientApp <port>
# Example:
./clientApp 8080
📦 Requirements
C++17 or later

Boost.Asio library

g++ and make tools installed
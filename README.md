# FizzApp - Real-Time Web Chat Application (Backend)

FizzApp Backend is the server-side component of the FizzApp real-time chat application. It handles the WebSocket connections, user authentication, and messaging functionality. The backend is built using **Node.js**, **Express.js**, and **Socket.IO**, ensuring real-time communication between users through WebSockets.

## Key Features:
- **WebSocket-based Real-Time Messaging**: Uses **Socket.IO** to establish real-time communication between users without the need for page refreshes.
- **User Authentication**: Manages user logins, ensuring each user has a unique identifier (userId) to handle messages.
- **Online User Tracking**: Tracks users who are currently connected and notifies all clients when users join or leave the chat.
- **Message Broadcasting**: Allows messages to be broadcasted to specific users or all connected clients in real time.

## Getting Started

### Prerequisites:
To run the FizzApp Backend, you'll need:
- **Node.js** v14 or higher
- **npm** (Node Package Manager) or **yarn**

### Installation:

1. Clone the repository:
   ```bash
   git clone https://github.com/Khoacoder22/Fizz-chat-BE.git

### Run
```bash
  npm start

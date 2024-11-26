# Real-Time Chat Application Chit Chat

A simple chat application where multiple users can send messages in real time. Built using **Node.js**, **Express**, and **WebSocket**.

## How to Run

1. Clone the repository and navigate to the project folder:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the server:
   ```bash
   node server/server.js
   ```

4. Open your browser and go to `http://localhost:3000`.

---

## How It Works

1. **Server**:
   - Handles WebSocket connections from clients.
   - Broadcasts messages to all users except the sender.
   - Users can set their names, which are displayed in the chat.

2. **Client**:
   - Connects to the server using WebSocket.
   - Allows users to enter their name before chatting.
   - Displays messages from others in real-time.

---

## Key Points

- Written using only basic libraries: **Express** for serving static files and **WebSocket** for real-time communication.
- Chat messages are sent as JSON to include both the user’s name and their message.
- Names are required to join the chat; the default is "Anonymous" if none is entered.

---

### Built By

Rishabh soni  
MITS Gwalior M.P.  
```

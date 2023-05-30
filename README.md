# Chat-app-using-MERN-Stack
# FrontEnd
- This repo consists of the Frontend part of a Realtime Chat Application built with the MERN stack.

# Features :
- Chat Rooms: Users should be able to create, join, and leave chat rooms.
- Real-Time Messaging: Messages sent by users should appear in the chat room in real time.
- Message History: The chat application should store the history of messages for each chat room, which should be visible to users when they join the room.
- Private Messaging: Users should be able to send private messages to other users.

# Technology Used:
- Database - MongoDB
- Backend - Express.js & Node.js
- Frontend - React.js
- Real-time messages - Socket.io

# How to use this:
- Clone the repo
- Enter the directory
- Install dependencies (yarn install)
- Change .env.example file
    - change file name to .env
    - go to MongoDB Atlas to create a cluster and change the MONGO_URI
    - change the CLIENT_URL to your local client port (ex. http://localhost:3000 for client running on port 3000)
    - generate random token for ACCESS/REFRESH_TOKEN_SECRET and also COOKIE_SIGNATURE
- Run the app (Yarn dev)

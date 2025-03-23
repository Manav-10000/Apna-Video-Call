# Apna Video Call 

## Overview
Apna Video Call is a Zoom-like video conferencing application built using the MERN (MongoDB, Express, React, Node.js) stack. This project enables users to create, join, and manage video calls seamlessly with real-time communication using WebRTC and Socket.io.

## Features
- User authentication and registration
- Create and join video meetings
- Real-time audio and video streaming
- Chat functionality during meetings
- Screen sharing
- Mute/unmute audio and video
- Responsive UI
- Secure communication with JWT authentication

## Tech Stack
### Frontend
- React.js
- Redux
- WebRTC
- Socket.io-client
- Tailwind CSS

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose ORM)
- Socket.io
- JWT Authentication

## Installation & Setup

### Prerequisites
Ensure you have the following installed:
- Node.js (v14+)
- MongoDB (local or cloud instance)
- npm or yarn

### Clone the Repository
```sh
git clone https://github.com/yourusername/apna-video-call.git
cd apna-video-call
```

### Backend Setup
1. Navigate to the backend folder:
```sh
cd backend
```
2. Install dependencies:
```sh
npm install
```
3. Set up environment variables in a `.env` file:
```
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
PORT=5000
```
4. Start the backend server:
```sh
npm start
```

### Frontend Setup
1. Navigate to the frontend folder:
```sh
cd ../frontend
```
2. Install dependencies:
```sh
npm install
```
3. Start the React application:
```sh
npm start
```

The application should now be running on `http://localhost:3000/`.

## Usage
- Register or log in to the platform.
- Create or join a meeting using the provided meeting ID.
- Utilize features like video/audio toggle, chat, and screen sharing.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

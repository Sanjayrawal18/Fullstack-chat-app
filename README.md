# Chat-App

A full-featured real-time chat application that allows users to send and receive messages and images instantly using WebSockets.

## Live demo:
https://fullstack-chat-app-1txh.onrender.com/login

## 🚀 Features

- Real-time communication with Socket.IO
- Image sharing with secure cloud storage using Cloudinary
- Clean, responsive user interface
- Scalable and easy to extend

## 🛠 Tech Stack

- Frontend: React.js
- Backend: Node.js, Express.js
- Real-Time: Socket.IO
- Cloud Storage: Cloudinary
- Styling: Tailwind CSS

## 🧪 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/Sanjayrawal18/Fullstack-chat-app.git
   
2. Install dependencies:

   ```powershell
   cd chat-app
   npm install

3. Create a .env file with necessary environment variables (e.g., Cloudinary keys, port).
   ```powershell
   MONGODB_URI=
   PORT=5001
   
   JWT_SECRET=
   
   
   CLOUDINARY_CLOUD_NAME=
   CLOUDINARY_API_KEY=
   CLOUDINARY_API_SECRET=

   NODE_ENV=development

5. Start the server and frontend:
   ```powershell
   cd frontend
   npm run dev

   cd backend
   npm run dev

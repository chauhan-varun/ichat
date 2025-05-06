# iChat - Real Time Chat Application

[![Live Demo](https://img.shields.io/badge/Live%20Demo-View%20App-brightgreen)](https://ichat-cobn.onrender.com)

A full-featured real-time chat application built using the MERN stack (MongoDB, Express, React, Node.js) with Socket.io for real-time communication.

## Features

-   🌟 **Modern Tech Stack**: MERN (MongoDB, Express, React, Node.js) + Socket.io + TailwindCSS + Daisy UI
-   🔐 **Secure Authentication**: JWT-based authentication and authorization
-   💬 **Real-time Messaging**: Instant messaging with Socket.io
-   🟢 **Online Status**: Real-time user online/offline status indicators
-   📱 **Responsive Design**: Works seamlessly on desktop and mobile devices
-   🔄 **State Management**: Global state handling with Zustand
-   🛡️ **Error Handling**: Comprehensive error handling on both client and server
-   🔍 **User Search**: Find and connect with other users

## Project Structure

```
ichat/
├── backend/                  # Server-side code
│   ├── controllers/          # Route controllers
│   ├── db/                   # Database connection
│   ├── middleware/           # Express middleware
│   ├── models/               # Mongoose models
│   ├── routes/               # API routes
│   ├── socket/               # Socket.io implementation
│   └── utils/                # Utility functions
├── frontend/                 # Client-side code
│   ├── public/               # Static files
│   └── src/
│       ├── assets/           # Images, sounds, etc.
│       ├── components/       # React components
│       ├── context/          # React context
│       ├── hooks/            # Custom React hooks
│       ├── pages/            # Page components
│       ├── utils/            # Utility functions
│       └── zustand/          # State management
```

## Prerequisites

- Node.js (v14+ recommended)
- MongoDB (local or Atlas)
- npm or yarn

## Installation

1. **Clone the repository**

```bash
git clone https://github.com/chauhan-varun/ichat.git
cd ichat
```

2. **Install server dependencies**

```bash
npm install
```

3. **Install client dependencies**

```bash
cd frontend
npm install
cd ..
```

4. **Create a .env file in the root directory with the following variables**

```
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
NODE_ENV=development
```

## Running the Application

### Development Mode

**Run backend server**
```bash
npm run server
```

**Run frontend (in a separate terminal)**
```bash
cd frontend
npm run dev
```

### Production Mode

**Build the app**
```bash
npm run build
```

**Start the app**
```bash
npm start
```

## Technologies Used

### Backend
- Node.js & Express.js - Server framework
- MongoDB & Mongoose - Database and ODM
- Socket.io - Real-time communication
- JWT - Authentication
- bcrypt.js - Password hashing

### Frontend
- React.js - UI library
- Vite - Build tool
- TailwindCSS & Daisy UI - Styling
- Socket.io-client - Real-time communication
- Zustand - State management

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the ISC License.

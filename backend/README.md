# CodeCanvas - Backend API & Real-Time Server

The backend service for **CodeCanvas**, providing RESTful APIs for authentication, discussions, solutions, and contests, alongside a Socket.io WebSocket server for real-time collaborative coding and room chat.

## 🛠️ Technologies
- **Node.js** & **Express 5**
- **MongoDB** & **Mongoose 8**
- **Socket.io 4.8**
- **JWT (JSON Web Tokens)** & **Bcrypt**
- **Axios** (Piston Judge API & LeetCode integrations)

## 🚀 Quick Start
```bash
# Install dependencies
npm install

# Copy environment variables
cp .env.example .env

# Run in development mode
npm run dev

# Run in production mode
npm start
```

## ⚙️ Environment Configuration (`.env`)
```env
PORT=3000
MONGODB_URI=mongodb://localhost:27017/codecanvas
JWT_SECRET=your_jwt_secret_key_here
JUDGE_URL=https://emkc.org/api/v2/piston/execute
```

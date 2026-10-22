# CodeCanvas - Frontend Web Application

The frontend client for **CodeCanvas**, an interactive real-time collaborative coding platform, problem-solving workspace, and competitive programming dashboard.

## 🛠️ Technologies
- **React 19**
- **Vite 6**
- **CodeMirror 6** (`@uiw/react-codemirror` with Dracula theme)
- **Socket.io Client 4.8**
- **React Router DOM 7**
- **Lucide React** & **React Icons**

## 🚀 Quick Start
```bash
# Install dependencies
npm install

# Copy environment variables
cp .env.example .env

# Run Vite development server
npm run dev

# Build for production
npm run build
```

## ⚙️ Environment Configuration (`.env`)
```env
VITE_BACKEND_URL=http://localhost:3000
VITE_JUDGE=https://emkc.org/api/v2/piston/execute
VITE_API_URL=https://alfa-leetcode-api.onrender.com
```

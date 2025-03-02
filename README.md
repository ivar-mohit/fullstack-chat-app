# Fullstack Chat App

This web application provides **real-time chat features** using the MERN stack (MongoDB, Express.js, React.js, and Node.js).

## Features
- 🔥 Real-time messaging
- 📌 User authentication (JWT)
- 🧑‍💻 Online/Offline status
- 📄 Group chat functionality
- 💬 Message timestamps
- Secure Password Hashing

## Tech Stack
- Frontend: **React.js** + CSS Modules
- Backend: **Node.js + Express.js**
- Database: **MongoDB**
- Authentication: **JWT (JSON Web Tokens)**
- Real-time communication: **Socket.IO**

## Folder Structure
```
chat-app/
├─ backend/         # Node.js + Express API
│  ├─ config/      # DB & JWT configs
│  ├─ models/      # MongoDB Schemas
│  ├─ routes/      # API Routes
│  └─ server.js    # Main server file
│
├─ frontend/       # React app
│  ├─ src/
│  │  ├─ components/
│  │  ├─ pages/
│  │  └─ App.js
│  └─ package.json
│
└─ .env            # Environment Variables
└─ README.md       # Documentation
```

## Installation
### Prerequisites
- Node.js
- MongoDB
- Git

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/ivar-mohit/fullstack-chat-app.git
   cd fullstack-chat-app
   ```

2. Install dependencies:
   - Backend
   ```bash
   cd backend
   npm install
   ```
   - Frontend
   ```bash
   cd ../frontend
   npm install
   ```

3. Create `.env` files
- In `backend/.env`
```env
MONGO_URI=mongodb://localhost:27017/chatapp
JWT_SECRET=your_jwt_secret
PORT=5000
```

4. Run the Application
- Backend:
```bash
cd backend
npm start
```
- Frontend:
```bash
cd frontend
npm start
```

### Live Demo 🌐
👉 Check out the app here: [Fullstack Connect App](https://fullstack-chat-app-24ck.onrender.com)

### API Endpoints
| Method | Route             | Description       |
|--------|------------------|-----------------|
| POST   | /api/auth/register | Register User   |
| POST   | /api/auth/login    | Login User     |
| GET    | /api/messages      | Get Messages   |
| POST   | /api/messages      | Send Message   |

---

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---
**Made with ❤️ by Mohit Maravi**


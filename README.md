# 🎥 VirtuoCall — Real-Time Video Conferencing App  

**VirtuoCall** is a modern real-time video conferencing web application powered by **React**, **WebRTC**, **Socket.IO**, and **Material UI**.  
It allows users to create and join meetings with unique codes, chat during calls, and keep a history of their meetings—all within a secure and responsive interface.  

---

## 🚀 Features  

- ✅ High-quality **real-time video conferencing** via WebRTC  
- 💬 **In-call chat** powered by Socket.IO  
- 🔐 **User authentication** with secure token storage  
- 📅 **Meeting history** tracking for past sessions  
- 🎨 Sleek, responsive **Material UI** design  
- 🛡️ **Protected routes** using custom middleware  
- 🌐 Works seamlessly across **desktop and mobile**  

---

## 🛠️ Tech Stack  

### **Frontend**  
- React.js  
- React Router  
- Socket.IO Client  
- Material UI  

### **Backend**  
- Node.js  
- Express.js  
- Socket.IO Server  
- MongoDB + Mongoose  

---

## 📂 Project Structure  

```
Virtuo_Call/
│
├── backend/
│   ├── models/         # Database schemas
│   ├── routes/         # API routes
│   ├── controllers/    # Business logic
│   ├── socket/         # WebSocket setup
│   └── server.js       # Entry point
│
├── frontend/
│   ├── src/
│   │   ├── pages/      # React pages
│   │   ├── contexts/   # Context API
│   │   ├── utils/      # Helper functions
│   │   └── App.js      # Main app component
│   └── public/         # Static assets
│
├── .env
├── package.json
└── README.md
```

---

## ⚙️ Environment Variables  

Create a `.env` file inside the **backend/** directory and add the following:  

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLIENT_URL=http://localhost:3000
```

---

## 🧪 Getting Started Locally  

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/vishnuchaithanya1/Virtuo_Call.git
cd Virtuo_Call
```

### 2️⃣ Install dependencies  

**Backend:**  
```bash
cd backend
npm install
```

**Frontend:**  
```bash
cd ../frontend
npm install
```

### 3️⃣ Configure `.env`  
Fill in your MongoDB URI and JWT secret as described above.  

### 4️⃣ Run the project  

In one terminal (backend):  
```bash
cd backend
npm start
```

In another terminal (frontend):  
```bash
cd frontend
npm start
```

The app will be available at 👉 **http://localhost:3000**  

---

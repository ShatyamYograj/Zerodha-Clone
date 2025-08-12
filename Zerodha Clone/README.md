# Zerodha Clone - Full Stack Trading App

A full-stack clone of Zerodha, India's leading trading platform, built using the MERN (MongoDB, Express.js, React, Node.js) stack. This project demonstrates user authentication, responsive frontend UI, dashboard functionality for orders/holdings/positions, and integration with a backend API and MongoDB database.

---

## 🚀 Features

- 🔐 User Signup with validation
- 📊 User Dashboard after login
- 📈 View Holdings, Positions, and Orders
- 🧾 Place and Save Orders
- ⚙️ Built with modular React components
- 🌐 API built using Express & Node.js
- 💾 MongoDB for persistent storage

---

## 🧩 Tech Stack

- **Frontend:** React, Bootstrap, React Router DOM
- **Dashboard:** React with custom components
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose ODM)
- **Others:** Axios, dotenv, CORS, body-parser

---

## 🗂️ Folder Structure

Zerodha Clone/
│
├── frontend/ # Landing page and Signup UI
├── dashboard/ # Post-login dashboard (Holdings, Orders, etc.)
└── backend/ # Express API and MongoDB integration


---

## 🛠️ Installation & Local Setup

### Prerequisites:

- Node.js and npm installed
- MongoDB connection string
- Git installed

---

### 1. Clone the Repository


git clone https://github.com/YOUR-USERNAME/zerodha-clone.git
cd zerodha-clone
2. Setup Backend

cd backend
npm install
# Create a .env file and add:
# MONGO_URL=your_mongodb_uri
# PORT=3002
npm start
3. Setup Frontend

cd ../frontend
npm install
npm start
4. Setup Dashboard

cd ../dashboard
npm install
npm start


💡 Future Enhancements
Add Login with JWT authentication

Add live stock API integration

Add Buy/Sell functionality

Responsive mobile view

👨‍💻 Author
Shatyam Yograj
GitHub

📄 License
This project is licensed under the MIT License.
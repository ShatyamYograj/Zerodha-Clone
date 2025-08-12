# Zerodha MERN Clone

A full-stack stock trading platform inspired by [Zerodha](https://zerodha.com), built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js).  
The application allows user signup/login, secure backend API handling, and a responsive dashboard showing holdings, positions, and orders — closely replicating the real Zerodha UI.

---

## 📂 Project Structure

Zerodha-MERN/
├── frontend/ # React-based landing page and signup
├── dashboard/ # Post-login user dashboard UI
├── backend/ # Express + MongoDB API
└── README.md # Project documentation


---

## 🚀 Features

- **User Authentication** — Secure signup/login flow with password hashing (bcrypt) and JWT authentication.
- **Responsive UI** — Fully responsive layouts using Bootstrap/Tailwind CSS.
- **Stock Dashboard** — Displays user holdings, positions, and orders.
- **RESTful APIs** — Well-structured API endpoints for data handling.
- **MongoDB Database** — Stores user data and stock details securely.

---

## 🛠 Tech Stack

**Frontend:** React.js, Bootstrap/Tailwind CSS, JavaScript  
**Backend:** Node.js, Express.js  
**Database:** MongoDB (Atlas or local)  
**Other Tools:** Git, GitHub, JWT, bcrypt

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/zerodha-mern.git
cd zerodha-mern
```
2️⃣ Backend Setup

cd backend
cp .env.example .env   # create a local .env file
npm install
npm run dev            # or: node index.js

Backend .env variables:

MONGO_URI=your-mongodb-connection-string
JWT_SECRET=your-secret-key
PORT=5000


3️⃣ Frontend Setup

cd frontend
npm install
npm start

4️⃣ Dashboard Setup

cd dashboard
npm install
npm start

📌 API Endpoints (Example)

| Method | Endpoint       | Description             |
| ------ | -------------- | ----------------------- |
| POST   | /api/signup    | Register a new user     |
| POST   | /api/login     | Authenticate user       |
| GET    | /api/holdings  | Get user holdings data  |
| GET    | /api/positions | Get user positions data |


📄 License
This project is open-source and available under the MIT License.

👤 Author
Shatyam Yograj

GitHub: @ShatyamYograj
LinkedIn: https://www.linkedin.com/in/shatyam-yograj-54588a259/

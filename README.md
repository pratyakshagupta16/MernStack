# 💊 ReMedi – Medicine Reminder App

ReMedi is a **MERN Stack medicine reminder web application** that helps users manage their medicines, receive reminders, and track daily medication progress.

The app allows users to securely log in, schedule medicines, and monitor their adherence through a **simple and responsive dashboard**.

---

# 🚀 Features

* 🔐 **JWT Authentication**
* 👤 **User-specific medicine tracking**
* 💊 **Add, edit, delete medicines**
* ⏰ **Medicine scheduling with repeat options**
* 📊 **Dashboard with daily & weekly summary**
* 🔔 **Browser reminder notifications**
* ✔ **Mark medicines as taken**
* 🌙 **Dark mode UI**

---

# 🛠 Tech Stack

### Frontend

* React
* Vite
* Axios
* CSS

### Backend

* Node.js
* Express.js
* JWT Authentication

### Database

* MongoDB
* Mongoose

### Tools

* Git
* GitHub
* Postman



---

# ⚙ Installation

## 1️⃣ Clone Repository

git clone https://github.com/pratyakshagupta16/MernStack.git
cd MernStack/remedi


---

# 🔧 Backend Setup


cd backend
npm install


Create '.env' file inside **backend folder**


PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/remedi
JWT_SECRET=your_secret_key


Run backend server


npm run dev

Server runs on


http://localhost:5000


---

# 🎨 Frontend Setup

Open new terminal


cd frontend
npm install
npm run dev


Frontend runs on


http://localhost:5173


---

# 📌 How to Use

1. Signup for a new account
2. Login with your credentials
3. Add medicines and set reminder times
4. Track medicines in the dashboard
5. Mark medicines as taken

---

# 🔎 API Endpoints

### Authentication


POST /api/auth/register
POST /api/auth/login


### Medicines


GET /api/medicines
POST /api/medicines
PUT /api/medicines/:id
DELETE /api/medicines/:id
POST /api/medicines/:id/mark-taken


---

# 📈 Future Improvements

* Email notifications
* Mobile responsive UI
* Cloud deployment
* Doctor prescription integration
* Mobile app version

---

# 👨‍💻 Author

**Pratyaksha Gupta**

GitHub
https://github.com/pratyakshagupta16

---


# 💰 Cash Trail – Expense Tracker

**Cash Trail** is a full-stack web application that helps users manage their income and expenses. It features secure authentication, transaction tracking, budget management, and interactive dashboards.

---

## 🚀 Features

- 🔐 **User Authentication** – Register & login (JWT-based)  
- 💸 **Expense & Income Management** – Track daily transactions  
- 📊 **Interactive Dashboard** – Charts & summaries of financial activity  
- 🎯 **Budget Management** – Compare income vs. expenses  
- 📂 **Excel Import/Export** – Manage financial data easily  
- 📱 **Responsive UI** – Built with TailwindCSS for modern design  

---

## 🛠️ Tech Stack

- **Frontend:** React (Vite), TailwindCSS, Recharts  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose)  
- **Authentication:** JWT, bcrypt  
- **File Handling:** Multer, XLSX  

---

## 📂 Project Structure

```
CASH_TRAIL-main/
│── backend/                # Express.js server
│   ├── config/             # DB config
│   ├── controllers/        # Logic for auth, expenses, income, dashboard
│   ├── middleware/         # Auth & file upload
│   ├── models/             # Mongoose schemas
│   ├── server.js           # App entry point
│   └── package.json        # Backend dependencies
│
│── frontend/
│   └── Cash_Trail/
│       ├── src/
│       │   ├── components/ # UI Components
│       │   ├── pages/      # App Pages
│       │   ├── context/    # Global state
│       │   ├── hooks/      # Custom hooks
│       │   └── App.jsx     # Main app
│       ├── index.html      # Vite entry
│       ├── package.json    # Frontend dependencies
│       └── tailwind.config.js
```

---

## ⚙️ Installation & Setup

### 🔹 Backend Setup
1. Navigate to backend folder:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure `.env` file:
   ```
   PORT=5000
   MONGO_URI=your_mongodb_connection
   JWT_SECRET=your_secret_key
   ```
4. Run backend server:
   ```bash
   npm start
   ```
   Runs at 👉 `http://localhost:5000`

---

### 🔹 Frontend Setup
1. Navigate to frontend folder:
   ```bash
   cd frontend/Cash_Trail
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run frontend app:
   ```bash
   npm run dev
   ```
   Runs at 👉 `http://localhost:5173`

---

## 📖 Usage

1. Open frontend in browser (`http://localhost:5173`)  
2. Register or login to your account  
3. Add income and expenses  
4. Explore dashboard charts & reports  
5. Export/import `.xlsx` files if needed  

---

## 🤝 Contributing

1. Fork the repo  
2. Create feature branch (`git checkout -b feature-name`)  
3. Commit changes (`git commit -m "Add feature"`)  
4. Push branch (`git push origin feature-name`)  
5. Open Pull Request  

---

## 📜 License

Licensed under the **MIT License**.  

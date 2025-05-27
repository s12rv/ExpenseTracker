# 💸 Expense Tracker

Expense Tracker is a comprehensive full-stack web application crafted to empower users in managing their personal finances with ease and clarity. Effortlessly record your income and expenses, visualize your financial journey, and gain actionable insights into your spending habits. The app features a sleek, modern interface and a robust backend for a seamless and secure experience.

---

## ✨ Features

- **🔐 User Authentication:** Secure registration and login with JWT-based authentication.
- **👤 Profile Management:** Upload and update your profile photo for a personalized touch.
- **💰 Income & Expense Tracking:** Add, view, and delete detailed income and expense records.
- **📊 Dashboard:** Instantly see your total balance, recent transactions, and a financial summary.
- **📈 Data Visualization:** Interactive charts and graphs to help you understand your financial patterns.
- **📥 Export Data:** Download your income and expense data as Excel files for offline analysis or backup.
- **📱 Responsive Design:** Enjoy a smooth experience on desktops, tablets, and mobile devices.
- **⚡ Modern UI:** Built with React, Vite, and Tailwind CSS for speed and style.

---

## 🛠️ Technology Stack

- **Frontend:** React, Vite, Tailwind CSS, Recharts, Axios
- **Backend:** Node.js, Express.js, MongoDB, Mongoose, Multer, JWT, XLSX

---

## 📁 Folder Structure

```
ExpenseTracker-1/
│
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   ├── .env
│   ├── server.js
│   └── package.json
│
└── frontend/
    └── expense-tracker/
        ├── src/
        ├── public/
        ├── index.html
        ├── package.json
        └── vite.config.js
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn
- MongoDB (local installation or cloud instance)

### Backend Setup

1. **Install dependencies:**
   ```sh
   cd backend
   npm install
   ```

2. **Configure environment variables:**
   - Create a `.env` file in the `backend` folder.
   - Add your MongoDB connection string and JWT secret, for example:
     ```
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

3. **Start the backend server:**
   ```sh
   npm run dev
   ```
   The backend will run on [http://localhost:8000](http://localhost:8000) by default.

### Frontend Setup

1. **Install dependencies:**
   ```sh
   cd frontend/expense-tracker
   npm install
   ```

2. **Start the frontend development server:**
   ```sh
   npm run dev
   ```
   The frontend will run on [http://localhost:5173](http://localhost:5173) by default.

---

## 📝 Usage

1. Open your browser and go to [http://localhost:5173](http://localhost:5173).
2. Register a new account or log in with your existing credentials.
3. Add your income and expense entries with relevant details.
4. Explore your financial dashboard to see summaries and interactive charts.
5. Download your data as Excel files for backup or further analysis.

---

## 🤝 Contributing

Contributions are welcome! If you find a bug or want to suggest a new feature, please open an issue or submit a pull request. Your feedback helps make this project better for everyone.

---

## 📄 License

This project is intended for educational and personal use.

---

**Developed with ❤️ using React, Node.js, and MongoDB. Manage your money, master your future!**

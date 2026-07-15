# 💳 Banking Transaction System

A secure backend Banking Transaction System built with **Node.js**, **Express.js**, and **MongoDB**. The project demonstrates authentication, account management, secure money transfers, and transaction history using RESTful APIs.

---

## 🚀 Features

- User Registration & Login
- JWT Authentication
- Refresh Token Authentication
- Secure Logout
- Bank Account Creation
- View Account Balance
- Money Transfer Between Accounts
- Transaction History
- RESTful API Architecture
- MongoDB Database Integration
- Error Handling & Validation

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT (JSON Web Token)
- bcrypt.js
- Cookie Parser
- dotenv

---

## 📁 Project Structure

```
Backend/
│
├── src/
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── services/
│   └── app.js
│
├── server.js
├── package.json
└── .env
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/banking-transaction-system.git
```

### 2. Navigate to the project

```bash
cd banking-transaction-system
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure environment variables

Create a `.env` file in the root directory.

```env
PORT=3000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

JWT_REFRESH_SECRET=your_refresh_secret
```

### 5. Start the server

```bash
npm start
```

or

```bash
npm run dev
```

---

## 🔑 Authentication APIs

### Register

```
POST /api/auth/register
```

### Login

```
POST /api/auth/login
```

### Logout

```
POST /api/auth/logout
```

---

## 🏦 Account APIs

### Create Account

```
POST /api/accounts
```

### Get My Accounts

```
GET /api/accounts
```

### Check Balance

```
GET /api/accounts/:id/balance
```

---

## 💸 Transaction APIs

### Transfer Money

```
POST /api/transactions
```

### Transaction History

```
GET /api/transactions
```

---

## 🔒 Security

- JWT Authentication
- Refresh Tokens
- Password Hashing using bcrypt
- Protected Routes
- Input Validation
- Error Handling

---

## 📌 Future Improvements

- Email Verification
- OTP Authentication
- Admin Dashboard
- Account Statements (PDF)
- Notifications
- Unit Testing
- Docker Support
- CI/CD Pipeline

---

## 👨‍💻 Author

**Muhammad Rashid Khan**

GitHub: github.com/rashii007

LinkedIn: linkedin.com/in/rashid-khan-8643b3380

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

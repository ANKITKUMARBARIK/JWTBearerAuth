
# 🔐 JWTBearerAuth

A secure and professional authentication system using **JWT (JSON Web Tokens)** passed in the **Authorization Bearer header**. Built with Node.js and Express, this API enables safe login, token-based access control, and middleware-protected routes.

---

## 📦 Features

- 🧾 User Signup & Login
- 🔐 JWT Token-based Authentication
- 📩 Token sent via `Authorization: Bearer <token>` header
- 🔒 Protected Routes using Middleware
- ⚙️ Clean and modular folder structure
- ❌ Logout by removing token on client side

---

## 📁 Project Structure

```
JWTBearerAuth/
│
├── controllers/       # Logic for handling requests
├── middleware/        # Token verification middleware
├── routes/            # API route handlers
├── utils/             # Helper functions
├── .env               # Environment variables
├── server.js          # Application entry point
└── package.json       # Project metadata and dependencies
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/ANKITKUMARBARIK/JWTBearerAuth.git
cd JWTBearerAuth
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Setup Environment Variables

Create a `.env` file in the root directory:

```
PORT=5000
JWT_SECRET=your_jwt_secret
```

### 4. Start the Server
```bash
npm start
```

---

## 🔐 How It Works

- On login, server returns a JWT token.
- Client stores the token (e.g., in localStorage).
- For protected routes, client sends token as a header:
  ```
  Authorization: Bearer <token>
  ```
- Middleware verifies the token before granting access.

---

## 🛠️ Tech Stack

- **Node.js**
- **Express.js**
- **jsonwebtoken**
- **dotenv**

---

## 📄 License

This project is licensed under the [GNU License](LICENSE).

---

## 🧑‍💻 Author

Made with ❤️ by [Ankit Kumar Barik](https://github.com/ANKITKUMARBARIK)

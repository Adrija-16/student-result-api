# 🎓 Student Result Management Backend

A secure Node.js + Express + MongoDB backend for handling user registration, login, and JWT authentication.

## 📦 Tech Stack
- Node.js
- Express.js
- MongoDB (via Mongoose)
- bcrypt (for password hashing)
- JWT (for token-based auth)
- dotenv (for config)

## 🚀 How to Run

1. Clone this repo
2. Run `npm install`
3. Create a `.env` file with:
```env
PORT=5000
MONGO_URI=mongodb+srv://admin:AdrijaMngoDB16@@cluster0.pfs1dfm.mongodb.net/studentdb?retryWrites=true&w=majority&appName=Cluster0
JWT_SECRET=supersecretkey123
4. Start server:
node index.js


## 📬 API Endpoints

| Method | Endpoint              | Description          |
|--------|-----------------------|----------------------|
| POST   | /api/auth/register    | Register new user    |
| POST   | /api/auth/login       | Login & get token    |

## 👥 Team
- Backend Developer: Adrija Halder


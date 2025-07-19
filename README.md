# Student Result Management System (Backend)

This is a RESTful API built with Node.js, Express, and MongoDB for handling student authentication (register/login). 
The system can be extended to manage student results, users, and admin access.

## 🔗 Live URL
Hosted on Render:  
➡️ [https://student-result-api-gh7z.onrender.com](https://student-result-api-gh7z.onrender.com)

## 🚀 Tech Stack
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- dotenv
- Render (for deployment)

## 📂 Features
- ✅ User Registration
- ✅ User Login
- ✅ MongoDB connection
- 📡 REST API with JSON


## 📬 API Endpoints

| Method | Endpoint             | Description                 |
| ------ | -------------------- | --------------------------- |
| POST   | `/api/auth/register` | Register new user           |
| POST   | `/api/auth/login`    | Login & get JWT token       |
| POST   | `/api/students`      | Add a new student (auth)    |
| GET    | `/api/students`      | Get all students (auth)     |
| GET    | `/api/students/:id`  | Get a student by ID (auth)  |
| PUT    | `/api/students/:id`  | Update student by ID (auth) |
| DELETE | `/api/students/:id`  | Delete student by ID (auth) |


### Register a User
`POST /api/auth/register`

**Request Body:**
```json
{
  "username": "admin",
  "email": "adrijahalder838@gmail.com",
  "password": "AdrijaMngoDB16@"
}
```

### Login
`POST /api/auth/login`

**Request Body:**
```json
{
  "email": "adrijahalder838@gmail.com",
  "password": "AdrijaMngoDB16@"
}
```

## 🧪 Testing
Tested using Postman with all successful responses.

## 🛠️ Setup Locally
```bash
git clone https://github.com/Adrija-16/student-result-api.git
cd student-result-api
npm install
npm start
```

Create a `.env` file with:
```
MONGO_URI=mongodb+srv://admin:AdrijaMngoDB16%40@cluster0.pfs1dfm.mongodb.net/studentdb?retryWrites=true&w=majority&appName=Cluster0
PORT=5000
```

## 👤Backend Developer
- Adrija Halder
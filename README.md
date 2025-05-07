# 🔐 Login & Signup Authentication App (MERN Stack)

A beginner-friendly user authentication system using the **MERN** stack – MongoDB, Express.js, Node.js (React.js is optional and not included in this version). It provides user registration and login functionality with secure password handling.

---

## 🚀 Features

- User Signup & Login
- Password Hashing using `bcrypt`
- Data storage using MongoDB and `mongoose`
- Server built with `Express.js`
- Simple UI using `EJS` + `Bootstrap 5`

---

## 📁 Project Structure

project-folder/
│
├── src/
│ ├── index.js # Express app entry point
│ ├── models/User.js # Mongoose schema
│ ├── routes/auth.js # Auth logic (signup/login)
│ └── views/ # EJS Templates
│ ├── login.ejs
│ ├── signup.ejs
│ └── home.ejs
│
├── .env # Environment variables (Mongo URI, Port)
├── package.json


---

## 🔧 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2. Install dependencies
bash
Copy
Edit
npm install
3. Add a .env file in the root directory
env
Copy
Edit
PORT=6000
MONGO_URI=mongodb://localhost:27017/your-database-name
4. Run the app
bash
Copy
Edit
npm start
🧪 Test the App
Visit: http://localhost:6000/signup – to sign up

Visit: http://localhost:6000/ – to log in

📦 Tech Stack
Node.js

Express.js

MongoDB + Mongoose

EJS for frontend rendering

Bootstrap 5 for styling

bcrypt for password hashing

dotenv for environment configs



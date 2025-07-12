# SocialHub Express 🗨️

A lightweight social web application built using Node.js, Express, MongoDB, and EJS templates. Users can register, log in, create/edit posts, and like/unlike posts. Sessions are handled using JWTs stored in cookies.

---

## ✨ Features

- ✅ User registration and login with password hashing (bcrypt)
- ✅ JWT-based authentication with cookie storage
- ✅ Create, edit, and delete posts
- ✅ Like/Unlike posts
- ✅ Profile page showing user details and posts
- ✅ Clean UI with TailwindCSS

---

## 🔧 Tech Stack

- **Backend:** Node.js, Express
- **Database:** MongoDB (with Mongoose)
- **Frontend:** EJS Templates + TailwindCSS
- **Auth:** bcrypt, JWT, cookies

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/socialhub-express.git
cd socialhub-express

2. Install dependencies
npm install

3. Setup MongoDB
Make sure MongoDB is running locally. The app uses:

mongodb://127.0.0.1:27017/miniproject
4. Run the application
node index.js
App will start on http://localhost:3000

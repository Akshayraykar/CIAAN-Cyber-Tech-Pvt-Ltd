# CIAAN-Cyber-Tech-Pvt-Ltd
Assignment


# 🌐 Mini LinkedIn - Community Platform

This is a full-stack LinkedIn-like mini community platform built for the Full Stack Development Internship assignment at CIAAN Cyber Tech Pvt Ltd.

Users can register, log in, update their profile, and create or view public posts.

---

## ✅ Features

- 🔐 **User Authentication**
  - Register / Login using Email and Password
  - JWT-based secure login
- 👤 **Profile Management**
  - Profile includes name, email, and bio
  - View any user's public profile and their posts
- 📝 **Post Feed**
  - Create and view text-only posts
  - Public home feed with post timestamps and author names
- 📱 Responsive UI

---

## 🛠️ Tech Stack Used

- **Frontend:** React.js (with Axios, React Router)
- **Backend:** Node.js with Express
- **Database:** MongoDB (with Mongoose)
- **Authentication:** JWT (JSON Web Token)
- **Deployment:**
  - Frontend: Vercel
  - Backend: Render

---

## 🔗 Live Demo Links

- **Frontend:** [https://mini-linkedin.vercel.app](https://mini-linkedin.vercel.app)
- **Backend:** [https://mini-linkedin-api.onrender.com](https://mini-linkedin-api.onrender.com)

---

## 👤 Demo Login

Email: demo@example.com
Password: demopass123

yaml
Copy
Edit

> You can also register a new user and explore the platform freely.

---

## 🚀 How to Run Locally

### 1. Clone the repository:

```bash
git clone https://github.com/Akshayraykar/mini-linkedin.git
cd mini-linkedin
2. Setup Backend
bash
Copy
Edit
cd server
npm install
✅ Create a .env file inside the server/ folder:

ini
Copy
Edit
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
bash
Copy
Edit
npm start
Server will run at: http://localhost:5000

3. Setup Frontend
bash
Copy
Edit
cd ../client
npm install
npm start
App will run at: http://localhost:3000

📁 Project Structure
bash
Copy
Edit
mini-linkedin/
├── client/       # React frontend
│   └── src/
├── server/       # Node.js backend
│   └── routes/
│   └── models/
│   └── controllers/
├── README.md
✨ Extra Features
Toast notifications

Clean UI with CSS modules

Proper error handling and validation

📞 Contact
Developed by Akshay Raykar

Email: akshayraykar4522@gmail.com

GitHub: https://github.com/Akshayraykar

LinkedIn: https://www.linkedin.com/in/akshayraykar22/

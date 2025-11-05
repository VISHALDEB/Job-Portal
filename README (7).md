# 🧑‍💼 Job Portal

A full-stack web application that connects **job seekers** with **employers** — allowing users to browse, apply, and post jobs easily.  
Built using **React.js**, **Node.js**, **Express**, and **MongoDB**, this project demonstrates a modern MERN-based workflow for building scalable recruitment platforms.

---

## 🚀 Features

### 👨‍💻 For Job Seekers
- View all active job listings
- Search & filter jobs by title, company, or location
- Apply for jobs directly through the portal
- Manage profile and track applications

### 🏢 For Employers
- Post, edit, and delete job listings
- View candidate applications
- Manage company profiles and recruitment data

### ⚙️ General Features
- User Authentication (JWT-based login/register)
- Role-based access control (Admin, Employer, Candidate)
- Responsive design (mobile-friendly UI)
- RESTful API backend
- MongoDB integration for persistent storage

---

## 🛠️ Tech Stack

| Category | Technology |
|-----------|-------------|
| Frontend | React.js, HTML5, CSS3, Bootstrap |
| Backend | Node.js, Express.js |
| Database | MongoDB (Mongoose ORM) |
| Authentication | JSON Web Tokens (JWT) |
| Hosting | Render / Vercel / Netlify (optional) |
| Version Control | Git & GitHub |

---

## 📁 Folder Structure

```
Job-Portal/
│
├── client/               # React frontend
│   ├── src/
│   │   ├── components/   # Reusable UI components
│   │   ├── pages/        # Main page layouts
│   │   ├── services/     # API calls
│   │   └── App.js
│   └── package.json
│
├── server/               # Express backend
│   ├── models/           # Mongoose schemas
│   ├── routes/           # REST API routes
│   ├── controllers/      # Business logic
│   ├── config/           # DB & JWT setup
│   └── server.js
│
├── .gitignore
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/VISHALDEB/Job-Portal.git
cd Job-Portal
```

### 2️⃣ Install Dependencies
**For backend:**
```bash
cd server
npm install
```

**For frontend:**
```bash
cd ../client
npm install
```

### 3️⃣ Configure Environment Variables
Create a `.env` file in the `server/` directory with:
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4️⃣ Run the Application
In two separate terminals:
```bash
# Run backend
cd server
npm run dev

# Run frontend
cd client
npm start
```

---

## 🧠 Learning Objectives

This project demonstrates:
- CRUD operations using MERN stack
- JWT authentication and authorization
- REST API design principles
- Frontend-backend integration
- Deployment process on cloud platforms

---

## 🧩 Future Enhancements

- Add resume upload and parsing
- Integrate real-time notifications
- Add admin dashboard & analytics
- Include pagination and sorting
- Enhance UI with Tailwind or Material UI

---

## 📸 Screenshots (Optional)

_Add preview images of your project interface here once hosted_

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to fork this repo and submit a pull request.

---

## 🧑‍🏫 Author

**👤 Vishal Deb**  
💻 Final Year B.Tech (CSE) — Netaji Subhash Engineering College  
📬 [GitHub Profile](https://github.com/VISHALDEB)

---

## 🪪 License

This project is licensed under the **MIT License** — free to use and modify.

---

> ⭐ If you found this project helpful, consider giving it a star on GitHub!

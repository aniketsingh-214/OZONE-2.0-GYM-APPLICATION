# OZONE 2.0 – Gym Management App

A full-stack **MERN** (MongoDB, Express, React, Node) application featuring BMI tracking, session booking, and email notifications.

---

## 📁 Project Structure

```
OZONE-2.0-GYM-APPLICATION/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.js
│   ├── public/
│   └── vite.config.js
└── README.md
```

---

## ⚙️ Setup & Run Locally

### 1. Clone the Repo

```bash
git clone https://github.com/aniketsingh-214/OZONE-2.0-GYM-APPLICATION.git
cd OZONE-2.0-GYM-APPLICATION
```

### 2. ✅ Backend Setup

```bash
cd backend
npm install
```

* Create a `.env` file with variables:

  ```
  MONGODB_URI=<your_mongo_uri>
  PORT=5000
  EMAIL_USER=<your_email>
  EMAIL_PASS=<your_email_password>
  ```
* Start the server:

  ```bash
  npm start
  ```
* API runs on: `http://localhost:5000`

### 3. ✅ Frontend Setup

```bash
cd ../frontend
npm install
npm run dev
```

* App runs on: `http://localhost:5173` (default Vite port)

---

## 🔧 Available Scripts

| Directory | Command       | Description                        |
| --------- | ------------- | ---------------------------------- |
| backend   | `npm start`   | Starts Express server on PORT 5000 |
| frontend  | `npm run dev` | Launches Vite development server   |

---

## 💡 Features Overview

* **User Auth** via JWT
* **BMI & Progress Tracking**
* **Session Booking**
* **Email Notifications** using Nodemailer
* **Responsive UI** built with React

---

## 🚀 Next Steps

* Update `.env` with actual MongoDB URI and email credentials.
* Optionally run database migrations or seed data.
* Open your browser to `http://localhost:5173` and test the features.

---

🤝 Contact
Created by Aniket Singh — feel free to reach out via GitHub or email at aniketsingh7141340@gmail.com.

# 🎬 Netflix Clone

A full-stack Netflix Clone application built using **React**, **Node.js**, **Express**, and **MongoDB**.  

🔗 **Netflix-Clone Live URL:** https://netflix-clone-36lp.onrender.com/  
🔗 **GitHub Repository:** https://github.com/jigneshbarhate/Netflix-Clone  

---

## 🚀 Features

- User authentication (Signup & Login)
- Browse movies and shows
- Search functionality
- Responsive UI for all devices
- Secure backend APIs
- Environment-based configuration

---

## 🛠 Tech Stack

### Frontend
- React
- React Router
- Axios
- CSS

### Backend
- Node.js
- Express.js
- MongoDB (Atlas)
- JWT Authentication

### Deployment
- Main: **Render**

---

## 📂 Project Structure

```

Netflix-Clone/
│
├── backend/              # Node.js + Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
│
├── frontend/             # React frontend
│   ├── public/
│   ├── src/
│   └── package.json
│
├── .gitignore
└── README.md

````

---

## ⚙️ Local Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/jigneshbarhate/Netflix-Clone.git
cd Netflix-Clone
````

---

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file in the backend folder:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
TMDB_API_KEY=your_tmdb_api_key
```

Start backend server:

```bash
npm start
```

---

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
```

Create a `.env` file in the frontend folder:

```
REACT_APP_BACKEND_URL=http://localhost:5000
REACT_APP_TMDB_API_KEY=your_tmdb_api_key
```

Start frontend:

```bash
npm start
```

---

## 🌍 Deployment Details

### Backend (Render)

* Express server deployed on Render
* Environment variables configured in Render dashboard
* Live API base URL:

  ```
  https://netflix-clone-36lp.onrender.com
  ```

---

## 🔗 Sample API Endpoints

| Method | Endpoint         | Description        |
| ------ | ---------------- | ------------------ |
| POST   | `/auth/signup`   | Register user      |
| POST   | `/auth/login`    | Login user         |
| GET    | `/movies`        | Fetch movies       |

---

## 👤 Author

**Jignesh Barhate**
GitHub: [https://github.com/jigneshbarhate](https://github.com/jigneshbarhate)

---

## ⭐ Acknowledgements

* TMDB API for movie data
* Render for deployment

---

⭐ If you like this project, don’t forget to star the repository!

```


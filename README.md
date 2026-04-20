# 🎬 Netflix Clone

A full-stack Netflix Clone application built using **React**, **Node.js**, **Express**, and **MongoDB**.  

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

## 🌍 Deployment Instructions

### 1️⃣ Backend (Render)
1.  Sign in to [Render](https://render.com/).
2.  Click **New +** > **Web Service**.
3.  Connect your GitHub repository.
4.  Configure the service:
    - **Name**: `netflix-clone-api`
    - **Root Directory**: `(leave blank if using render.yaml)`
    - **Build Command**: `npm install`
    - **Start Command**: `node backend/server.js`
5.  Add **Environment Variables**:
    - `MONGO_URI`: Your MongoDB connection string.
    - `JWT_SECRET`: A secure random string.
    - `TMDB_API_KEY`: Your TMDB API key.
    - `NODE_ENV`: `production`
    - `FRONTEND_URL`: Your Vercel deployment URL (e.g., `https://netflix-clone.vercel.app`).

### 2️⃣ Frontend (Vercel)
1.  Sign in to [Vercel](https://vercel.com/).
2.  Click **Add New** > **Project**.
3.  Import your GitHub repository.
4.  Configure the project:
    - **Framework Preset**: `Vite`
    - **Root Directory**: `frontend`
5.  Add **Environment Variables**:
    - `VITE_API_URL`: Your Render backend URL (e.g., `https://netflix-clone-api.onrender.com`).
6.  Click **Deploy**.

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



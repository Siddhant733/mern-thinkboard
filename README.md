# 📝 MERN ThinkBoard

A full-stack MERN (MongoDB, Express, React, Node.js) notes application with Redis-powered rate limiting and full production deployment.

🌐 **Live Demo:**
https://mern-thinkboard-mif6.onrender.com/

---

## 🚀 Features

* Create Notes
* View All Notes
* Update Notes
* Delete Notes
* RESTful API
* MongoDB Database Integration
* 🚫 Rate Limiting using Redis (Upstash)
* CORS Handling
* Full-stack Deployment (Render)

---

## 🛠️ Tech Stack

### 🔹 Backend

* Node.js
* Express.js
* MongoDB (Mongoose)
* dotenv
* cors
* Upstash Redis
* Rate Limiter (API protection)

### 🔹 Frontend

* React
* Vite
* Axios
* Tailwind CSS
* DaisyUI

---

## 📁 Project Structure

mern-thinkboard/
│
├── backend/
│ ├── src/
│ │ ├── controllers/
│ │ ├── routes/
│ │ ├── models/
│ │ ├── middleware/
│ │ ├── config/
│ │ └── server.js
│
├── frontend/
│ ├── src/
│ ├── public/
│ └── dist/

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repo

```bash
git clone https://github.com/Siddhant733/mern-thinkboard.git
cd mern-thinkboard
```

### 2️⃣ Backend Setup

```bash
cd backend
npm install
npm run dev
```

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 🔐 Environment Variables

Create a `.env` file inside backend:

```env
MONGO_URI=your_mongodb_connection_string
PORT=5001

# Upstash Redis (for rate limiting)
UPSTASH_REDIS_REST_URL=your_redis_url
UPSTASH_REDIS_REST_TOKEN=your_redis_token
```

---

## 🌍 API Endpoints

| Method | Endpoint       | Description     |
| ------ | -------------- | --------------- |
| GET    | /api/notes     | Get all notes   |
| GET    | /api/notes/:id | Get single note |
| POST   | /api/notes     | Create note     |
| PUT    | /api/notes/:id | Update note     |
| DELETE | /api/notes/:id | Delete note     |

---

## 🚀 Deployment

* Backend & Frontend deployed on **Render**
* MongoDB hosted on **MongoDB Atlas**
* Rate limiting powered by **Upstash Redis**

---

## 🔐 Security

* Rate limiting to prevent abuse
* Environment variables for secrets
* CORS protection

---

## 📌 Future Improvements

* User Authentication (JWT)
* Notes sharing
* Search & filters
* UI animations

---

## 🙌 Author

**Siddhant**

GitHub: https://github.com/Siddhant733

---

## ⭐ Show Your Support

If you like this project, give it a ⭐ on GitHub!

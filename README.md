# 🧠 Sukuun – Mental Health Support Website

Sukuun is a full-stack web application focused on mental health awareness and support. The platform provides users with resources, interactive features, and a safe space to explore mental well-being.

---
AryanRana
## 🚀 Features

* 🔐 Google Authentication (Firebase)
* 📝 Blogs & Community Sharing
* 😂 Meme Generator (Fun + Engagement)
* 📚 Mental Health Resources
* 🧘 Relaxation & Wellness Pages
* 🧩 Interactive UI with React

---

## 🛠️ Tech Stack

### Frontend

* React.js
* HTML, CSS
* Vite

### Backend

* Node.js
* Express.js

### Database & Auth

* Firebase (Authentication + Firestore)

### APIs

* MemeGen API
* Joke API

---

## 📂 Project Structure

```
Sukuun_Mental_Health/
│
├── Backend/        # Express server
├── Frontend/       # React app
├── README.md
└── package.json
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/Aryanrana7/Sukuun_Mental_Health_Final.git
cd Sukuun_Mental_Health_Final
```

---

### 2️⃣ Setup Backend

```
cd Backend
npm install
node server.js
```

Server runs on:

```
http://localhost:5004
```

---

### 3️⃣ Setup Frontend

```
cd Frontend
npm install
npm run dev
```

Frontend runs on:

```
http://localhost:5173
```

---

## 🔐 Firebase Setup

1. Go to Firebase Console
2. Create a project
3. Enable **Google Authentication**
4. Copy your config and paste into:

```
Frontend/src/components/firebase.jsx
```

---

## 🧪 Environment Variables (Recommended)

Create `.env` file:

```
VITE_FIREBASE_API_KEY=your_key
VITE_FIREBASE_AUTH_DOMAIN=your_domain
```

---

## 📸 Screenshots

(Add your project screenshots here)

---

## 👨‍💻 Developer

**Aryan Rana**

---

## 📌 Future Improvements

* Chat support system
* AI-based mental health assistant
* User dashboards
* Deployment (Vercel / Render)

---

## 🌐 Deployment (Coming Soon)

---

## 📄 License

This project is for educational purposes.
